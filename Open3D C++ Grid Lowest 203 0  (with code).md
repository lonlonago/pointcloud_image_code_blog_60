##  First, the principle of the algorithm 

###  1. Introduction to the algorithm 

  Grid nadir filtering is done by dividing the 3D point cloud into a grid in the X-Y plane, and then finding the point with the smallest Z coordinate in each grid to represent the grid. If the grid has no point cloud, it will not produce a center point representing the grid point cloud like voxel filtering. 

###  2. Applicability 

  The lowest point filter of the grid can effectively filter the situation where the elevation information is interrupted, such as the vehicle parked under the tree, etc., which can effectively find the lowest point and prepare for the subsequent segmentation. However, if there are no vehicles under the tree or the ground point cannot be scanned, then the point of the grid may be the lowest point of the scanned leaf, which requires further processing. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574596688
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574596688
 ```  
###  1. Primitive point cloud 

![avatar]( 0a791eaa6b8b4e79af56908c61ce0bdc.png) 

###  2. Filtering results 

![avatar]( 55c82eb8897d41c5a9fa443828a9ef92.png) 

##  IV. Relevant references 

