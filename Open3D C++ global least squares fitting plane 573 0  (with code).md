##  First, the principle of the algorithm 

###  1. Algorithmic process 

  The least squares fitting plane believes that there is no error in the coefficient matrix of point cloud data. However, due to the limitation of observation conditions, there may be errors in the observation vector and coefficient matrix, so the least squares method is no longer optimal, but biased. Therefore, the overall least squares method can be used to fit the point cloud plane, and the parameters of the fitting plane can be solved by the singular value decomposition method. Assuming that the coordinates of a point obtained by scanning a plane are, considering that there are errors in the direction of the observation data, the plane equation is rewritten as: In the formula, the correction numbers in the direction are respectively, and the above formula can be obtained by sorting. In the formula, the formula (2) is expressed as the error equation in the form of: can be rewritten as 

In the formula, the limiting constraint expressed by it is: Singular value decomposition of the augmented matrix 

 In the formula, it can be seen from the matrix approximation theory that the population least squares estimate of the parameters is  

Since it is the eigenvector of the matrix, the singular value satisfies the relationship with the eigenvector. Further, the unit weight variance can be calculated to be  

###  2. References 

>  [1] Bo Huaizhi. Accuracy comparison and analysis of three point cloud data plane fitting methods [J]. Surveying and Mapping and Spatial Geographic Information, 2018, 41 (05): 206-208. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574520134
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574520134
 ```  
![avatar]( 84a49b2cd6874dfd81b88116e547f9e0.png) 

