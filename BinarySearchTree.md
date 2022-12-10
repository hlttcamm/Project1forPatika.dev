## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]-->Binary-Search-Tree/ write steps of this sorting(Ex:Like that same as , root=x and y is find at the right of root, z is find at the left of root..)

***If root is 3,***



                   3  
               /       \ 
              1          7   
            /  \        /  \ 
           0    2      5    8  
                      / \     \
                     4   6     9
                   
 - Step 1: '7' is placed to the right of '3' because it is greater than '3'.
 
 - Step 2: '5' is placed to the right of '3' because it is greater than '3', and to the left of '7' because it is less than '7'.
 
 - Step 3: '1' is placed to the left  of '3' because it is less than '3'.
 
 - Step 4: '8' is placed to the right of '3' because it is greater than '3', and to the right of '7' because it is greater than '7'.
 
 - Step 5: '6' is placed to the right of '3' because it is greater than '3', and to the left of '7' because it is less than '7',and to the right of '5' because it is
 greater than '5'.
 
 - Step 6: '0' is placed to the left  of '3' because it is less than '3',and to the left of '1' because it is less than '1'.
 
 - Step 7: '9' is placed to the right of '3' because it is greater than '3', and to the right of '7' because it is greater than '7',and to the right of '8' because it is
 greater than '8'.
 
 - Step 8: '4' is placed to the right of '3' because it is greater than '3', and to the left of '7' because it is less than '7',and to the left of '5' because it is
 less than '5'.
 
 - Step 9: '2' is placed to the left  of '3' because it is less than '3',and to the right of '1' because it is greater than '1'.