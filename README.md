# Decision-Trees

Trees are used in artificial intelligence to represent various concepts, including sentence structure, equations, game modes, and more. The decision tree classifier is a method of classifying or clustering data with a tree structure. The internal nodes (attributes) are tests performed on input patterns, and the final nodes (leaves) are the classes corresponding to that pattern. Each node is connected to the lower node through branches according to the values ​the attributes connected to that node can choose.

In the decision tree classifier, each input pattern takes a path from the initial node (root) downwards according to its value values and is finally determined by reaching one of the final nodes (leaves) of that pattern class. It is called the decision tree because it represents the decision-making process for determining the category of an input instance.
<br/><br/>

<p align="center">
  <img width="520" height="340" src="https://user-images.githubusercontent.com/66460485/128902873-bb27b651-2a87-472f-a4ba-2a1c1be46e5c.PNG">
</p>

# Dataset

The dataset used for the training and test simulations are features calculated from a digital image of a fine needle aspiration (FNA) of the breast mass. They describe the characteristics of the cell nucleus in the image. 30% of the dataset is saved for testing, and the evaluation metric is the jaccard_score function.

> Attributes for each cell nucleus

<ol>
<li>radius</li>
<li>texture </li>
<li>perimeter</li>
<li>area</li>
<li>smoothness</li>
<li>compactness </li>
<li>concave points </li>
<li>symmetry</li>
<li>fractal dimension</li>
</ol>

Classes are defined as the diagnosis of the cancer stage as malignant and benign.
