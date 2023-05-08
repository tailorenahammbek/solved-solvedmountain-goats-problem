Download Link: https://assignmentchef.com/product/solved-solvedmountain-goats-problem
<br>
abstractThree black mountain goats one direction on a narrow mountain ledge and encounter three white mountain goats going in the opposite direction. They stop with the space of a goat between the two lead animals. Mountain goats cannot (for the purposes of the puzzle) move backwards, but they are good jumpers. A mountain goat can either move forward into an empty space, jump over one mountain goat to an empty space, or jump over two mountain goats to an empty space. How can they all continue on their way?

We can abstract this to the following:

B B B_ W W W

Where each B represents a black mountain goat, each W represents a white mountain goat, and _ represents a blank space. Each B may move right into an adjacent _, jump over an intervening B or W into an _, or jump over two intervening B or W into an _. Each W may similarly move left the same way. The goal is to get all of the Bs to the right of all of the Ws.

Use the graph search program provided in class to build a state space solution to the problem. Is there a difference in the solution for a breadth-first versus depth-first traversal of the graph? What is the difference in the number of node generated and explored?

Extend your representation to handle any number of black and white goats – they don’t have to be the same number. Is the problem solvable for all such combinations?