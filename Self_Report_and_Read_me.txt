The software fully works to the best of my knowledge, except the bonus part. 

-------------------------------------------------------------------------------------------------------

1. The CHORD system starts with a single node. The number of nodes in the CHORD depends on the value of m. Initially it is 5, so total number of nodes in the CHORD can be 2^5 (0 to 31).

2. I have implemented in Python and written the code in Jupyter Notebook interface.

3. For the visualization, I have used Tkinter package. So, when user selects to view the CHORD system, it pops up in a new window not in the text output window. Please click on that to view the figure.

-------------------------------------------------------------------------------------------------------

4. When you run the code, you should see a brief intro of the system and a menu of how to do each operation (add/delete/lookup/view CHORD)

5. The starting node is 0, initially there is 2^5 available nodes to be added

6. When you choose to add a node, the system will randomly choose a node in between 0 to 2^5-1

7. The lookup function will show step by step how the lookup is going on. 

8. Only physical node from the CHORD can be deleted, logical node cannot be deleted (as expected)

9. In the visualization of CHORD, the view shows up in a new window and the green nodes are the physical nodes. 