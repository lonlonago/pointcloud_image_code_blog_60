##  First, the principle of the algorithm 

###  1. Overview of the principle 

  Farthest Point Sampling (FPS): As the name suggests, the point farthest from the previously sampled points is selected for each sample. It can better ensure that the sampled points have good coverage, so it is widely used in the field of point cloud segmentation (e.g., PointNet ++, PointCNN, PointConv, PointWeb). However, the computational complexity of FPS is that the amount of computation is square related to the number of points in the input point cloud. This suggests that FPS may not be suitable for processing large-scale point clouds. For example, when entering a large field attraction cloud with millions of points, it takes up to 200 seconds to downsample it to 10% of the original size using FPS. 

###  2. Implementation process 

###  3. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574586761
 ```  
Select the farthest point from the previous one by iteration. num_samples: number of sampling points. 

###  4. Algorithm source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574586761
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574586761
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574586761
 ```  
![avatar]( 907a412bad714d2e8c786a0df6f94c8c.png) 

