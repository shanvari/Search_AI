# Search_AI

The problem you are facing consists of an undirected graph. This graph has nodes
There are those that each node can choose one of the three colors green, red or black at any moment. At
First, the graph contains nodes with colors among the above three colors. At each stage, you can choose one of
selected nodes, and the ultimate goal of the problem is to turn all the nodes of the graph green.
Next, the behavior of the nodes after they are selected is explained according to the color of the node:
Green/Red Node:
By selecting a green or red node, the selected node and each of its neighboring nodes:
 If it is green, it will change color to red.
 If it is red, it will change color to green.
 o If any of the neighboring nodes of the selected node is black, that neighboring node is no
Change remains.
Black knot:
To achieve the goal of the problem, it is necessary that the black nodes somehow match one of the green colors.
turn red, then they can change color to normal.
By choosing a black node, the following steps happen:
1 Each of the neighboring nodes of this node, if it is green, it is red, and if it is red, it is red
Green changes, and if it is black it remains unchanged. 2. After changing the color of the neighbors, according to the color of the majority of the neighbors, one
The following situations happen for the selected black node:
• If the majority of neighbors are red, the black node will change color to red
Gives.
• Similarly, if the majority of neighbors are green, the black node is green
It changes color.
• Otherwise, the selected black node remains unchanged and black
