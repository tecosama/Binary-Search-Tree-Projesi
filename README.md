# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

# Step 1 Sorting (with merge)
## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
### [7, 5, 1, 8, 3] [6, 0, 9, 4, 2]
### [7, 5, 1] [8, 3] [6, 0, 9] [4, 2]
### [7, 5] [1] [8] [3] [6, 0] [9] [4] [2]
### [7] [5] [1] [8] [3] [6] [0] [9] [4] [2]
### [5,7] [1] [3,8] [0,6] [9] [2,4] 
### [1,5,7] [3,8] [0,6,9] [2,4] 
### [1,3,5,7,8] [0,2,4,6,9] 
### [0,1,2,3,4,5,6,7,8,9] 

# Step 2 Binary Search Tree
### [0,1,2,3,4,5,6,7,8,9] 
###         5
###      2      7
###    1  3    6  8
###   0     4       9
