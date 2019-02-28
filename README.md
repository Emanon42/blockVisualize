# blockVisualize
Simply modify original robotPath.hs to improve display.    
For use, just download and replace. NOTE: remember to backup!    
Example:    
```
badNodesList = [(1,5), (2,5), (3,5), (4,5), (4,4), (4,3)]

Please enter a start grid point (row, column):
(1,1)
Please enter an end grid point (row, column):
(6,6)
Which search method would you like to use?
1. Breadth First Search
2. Depth First Search
3. Depth Limited Search (Test at a depth limit of 40)
4. Iterative Deepening Search
5. Best First Search
6. A* Search
6
 x | x |    |    | o |  
  -   -   -   -   -   -  
    | x |    |    | o |  
  -   -   -   -   -   -  
    | x |    |    | o |  
  -   -   -   -   -   -  
    | x | o | o | o |  
  -   -   -   -   -   -  
    | x | x | x | x | x
  -   -   -   -   -   -  
    |    |    |    |    | x
 ```

