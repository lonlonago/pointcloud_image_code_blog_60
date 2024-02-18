##  I. Overview 

As the title, obtain the overlapping and non-overlapping areas of the point cloud. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574536527
 ```  
##  III. Display of results 

![avatar]( a88fdc0029b645b0b9a53b4b2f1102ea.png) 



--------------------------------------------------------------------------------

##  Function overview 

###   1. Main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574599026
 ```  
The SelectByIndex function implements the function of extracting point clouds based on the index. 

###   2. Source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574599026
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574599026
 ```  
##  III. Display of results 

![avatar]( 198b4139439845f5b715c0967a084a81.png) 



--------------------------------------------------------------------------------

##  I. Overview 

  Open3D's built-in farthest point sampling function Open3D (C++) FPS farthest point downsampling does not perform multi-threaded acceleration, and the sampling efficiency is low when the amount of point cloud data is large. On the basis of analyzing the principle of the algorithm and the source code, this paper gives the multi-threaded accelerated version of the C++ Open3D code implementation. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574512365
 ```  
##  III. Display of results 

![avatar]( 541d9335fe2249d18f06cefd7ebcf904.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Overview 

  The non-iterative method is used to calculate the normal vector from the variance matrix. The calculation speed is faster, but the numerical stability is not high. See the source code for the specific implementation process. 

###  2. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574577049
 ```  
###  3. Algorithm source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574577049
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574577049
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574577049
 ```  
![avatar]( 031f1477f3a044e9b02895987123f466.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Overview of the paper 

  Segmentation from point cloud data is essential in many applications, such as remote sensing, mobile robots, or autonomous cars. However, point clouds captured by 3-D distance sensors are often sparse and unstructured, which poses a challenge for efficient segmentation. A fast solution for segmentation of point cloud instances with small computation is missing. To this end, a new Fast Euclidean Clustering (FEC) algorithm is proposed, which applies a point clustering algorithm on the basis of existing clustering algorithms and avoids constantly traversing every point. 

###  2. Implementation process 

![avatar]( f11acd12a73b4a85804629075e21ce2b.png) 

   First, zero all the points in the point cloud, initialize the segmentation to 1, and then traverse all the points. When the traversal point is found to be 0, find the nearest associated point. If there is a point that is not 0, find the smallest value, which means there is a connection. If there is no value, assign it, and then traverse the nearest point. If you find other values greater than that, traverse all the points again, and then reset all other values to the value of. As shown in the figure below, the pseudocode process in the paper is very clear, just write the code with reference to the process.   

###  3. References 

>  [1] Cao Y , Wang Y , Xue Y , et al. FEC: Fast Euclidean Clustering for Point Cloud Segmentation[J]. arXiv e-prints, 2022. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574577652
 ```  
##  III. Display of results 

![avatar]( 32190d2560c04e199f0fe9116e31386d.png) 

##  IV. Experimental data 

Link: https://pan.baidu.com/s/1JdXGgBMRBk6Ynbx6-pfiUw Extraction code: oupg 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

  The code implements a way to eliminate the erroneous nearest neighbor matching point pairs caused by missing scanning by using bidirectional nearest neighbor search. 

###  1. Main function 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574562257
 ```  
For other functions, see: Open3D (C++) fast global registration (based on FPFH) 

###  2. References 

>  [1] Liu Rufei, Wang Fei, Ren Hongwei, Wang Minye, Yang Jiben. A laser point cloud registration method for road scenes using geographical entity target characteristics [J/OL]. China Laser: 1-20 [2022-09-04]. http://kns.cnki.net/kcms/detail/31.1339.tn.20220714.1202.010.html 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574562257
 ```  
##  III. Display of results 

![avatar]( b68036fcf47d43d189e165b0a250de72.png) 

 The test data used in this paper: Open3D algorithm test data.rar  

##  IV. Relevant links 

[1] Open3D(C++) 快速全局配准（基于FPFH） [2] Open3D(C++) ColoredICP彩色点云精配准 [3] Open3D(C++) GICP算法实现点云精配准 [4] Open3D(C++)计算点云配准的精度和重叠度 [5] Open3D(C++) 点到平面的ICP算法实现点云精配准 [6] Open3D(C++) ICP算法实现点云精配准 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Remarks 

>  Detailed algorithm introduction can be viewed in the original text: Zhou Q Y, Park J, Koltun V. Fast Global Registration [J] .2016. and point cloud matching algorithm, paper sharing Fast Global Registration, Fast Global Registration. 

###  2. References 

>  The following two papers are improvements to the algorithm [1] Shen Changjiang, Wu Yundong, Cai Guorong, Chen Shuili. Lidar point cloud registration method for multi-view buildings based on quaternary constraints [J]. Journal of Jimei University (Natural Science Edition), 2019, 24 (05): 393-400. [2] Shen Changjiang. Research on multi-view Lidar point cloud registration technology based on tuple constraints [D]. Jimei University, 2019. 

###  3. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574569157
 ```  
Fast Global Registration based on FPFH feature descriptor. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574569157
 ```  
parameterized constructor 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574569157
 ```  
##  III. Display of results 

![avatar]( c1d2a7df7a0346a497c02be4e8a82aa1.png) 

##  IV. Python code 

[1] Open3D 快速全局配准(Fast Global Registration) 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

![avatar]( da930f38238b49d5af7540cf1f0d2751.png) 

   The coordinates of the center of the circle, the radius of the circle, and the angle of a point X on the circle are known.  

Then the coordinates of the point can be expressed as: 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574583849
 ```  
##  III. Display of results 

![avatar]( 31245c67854f45cf8be781bc4d9037be.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

  By knowing the direction vector of a point and a straight line on a straight line, a standard straight line point cloud for algorithm testing can be generated according to mathematical principles. In the following example code, a point on a straight line is used as the center point to generate a spatial straight line point cloud, where the number of points is 100 and the interval between adjacent points is 0.1m. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574583043
 ```  
##  III. Display of results 

![avatar]( fdb59457875c463b98d34ddd3bd6bf9c.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

  There are many ways to generate a spherical point cloud. Marsaglia proposed a simple and easy implementation in 1972. It selects the sum from the independent uniform distribution over (-1, 1) and culls the points. From the remaining points, namely: 

 It is uniformly distributed on the surface of the unit sphere. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574576702
 ```  
##  III. Display of results 

![avatar]( 10615d3f4ad04a6b80bd17f78b6a7b48.png) 

##  IV. Reference link 

[1] http://mathworld.wolfram.com/SpherePointPicking.html 



--------------------------------------------------------------------------------

##  First, the coordinate maximum value 

  Obtaining the maximum and minimum values of point cloud coordinates is a very important operation in many point cloud processing algorithms. C++ version of Open3D can directly call numpy to find the maximum value unlike python. Therefore, this paper gives three methods for finding the maximum value of point cloud coordinates on the basis of learning the C++ 11 standard library, in order to deal with various development environments. 

##  Second, C++ std implementation 

###  1. Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574548707
 ```  
###  2. Results display 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574548707
 ```  
##  III. Eigen implementation 

Open3D is highly integrated with Eigen, and the preservation of coordinates and point clouds relies on Eigen :: Vector 3d and std :: vector. 

###  1. Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574548707
 ```  
###  2. Results display 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574548707
 ```  
##  IV. Call implementation 

###  1. Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574548707
 ```  
###  2. Results display 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574548707
 ```  


--------------------------------------------------------------------------------

##  Box filtering 

   Given the maximum value of the box coordinates, extracts the points inside and outside the box. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957458665
 ```  
##  III. Display of results 

###  1. Primitive point cloud 

![avatar]( 25d43a9d12ba4d69a7aeeea56d337120.png) 

###  2. Designated regional point cloud 

![avatar]( 046232f929bd4668a27a929b779e5340.png) 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Algorithm overview 

  The principle of GICP algorithm is to combine ICP algorithm and Point-to-plane ICP into a probabilistic framework model, perform point cloud registration based on this framework, and play a role similar to weights through the covariance matrix to eliminate the role of some bad corresponding points in the solution process. GICP has a wider application range than standard ICP, and under certain conditions, the GICP algorithm degenerates into a standard ICP algorithm. At the same time, if there is a unique solution, the minimum point is the global optimal solution, and the GICP algorithm degenerates into a standard ICP algorithm. 

>  There is an explanation of the principle of the algorithm in this blog: GICP Study Notes 

###  2. Algorithm flow 

  GICP is an extension of the "point-to-point" ICP and "point-to-plane" ICP methods. To improve the robustness of the registration, GICP uses the covariance matrix of the point cloud surface to construct the cost function of point cloud registration. Suppose we find two clusters of points in two 3D point clouds that are close neighbors to each other: = {} and = {}, where the sum matches each other. In probability theory, we assume that there are two clusters of points corresponding to each other = {} and = {}. So, it can be defined that the point cloud is generated by the following Gaussian distribution: Is the covariance matrix of each point. We define the rigid transformation matrix, and the registration error of each pair of corresponding points is as follows: because and belong to independent Gaussian distributions, then the distribution also belongs to the Gaussian distribution:  

Therefore, the cost function for computing the transformation matrix is:  

###  3. References 

>  [1] Lin Baowei, Wang Fasheng, Sun Yi. Point cloud scale estimation and registration algorithm based on SGICP [J]. Computer Applications and Software, 2018, 35 (05): 202-207. [2] Generalized-ICP [C]//Robotics: Science and Systems V, University of Washington, Seattle, USA, June 28 - July 1, 2009. 

###  4. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574552154
 ```  
This function implements the GICP registration algorithm. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574552154
 ```  
##  III. Display of results 

###  1. Primitive point cloud 

![avatar]( 53b984cf1b1f40cbb1bef4511d1be69f.png) 

###  2. Registration results 

![avatar]( 181f81a265c14aebaeb160c125cc7f3d.png) 

##  IV. Python code 

Open3D uses GICP to register point clouds 



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

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



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Overview of the principle 

  This paper presents a simple and fast operator, the "hidden" point removal operator, which determines the visible point in a point cloud from a given viewpoint. Visibility is determined without reconstructing the surface or estimating the normal. The results show that extracting the point located on the convex hull of the transformed point cloud is equivalent to determining the visible point. The operator is generic - it can be applied to point clouds in various dimensions, point clouds on point clouds, and viewpoints inside and outside point clouds. The results show that the operator is useful in point cloud visualization, viewpoint-dependent reconstruction, and shadow casting. 

###  2. References 

>  [1] Katz, Sagi, Tal, Ayellet, Basri, & Ronen. (2007). Direct visibility of point sets. Tog. 

###  3. Main functions 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957458566
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957458566
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957458566
 ```  
![avatar]( 6608b73275aa479a93ed2cee3126732c.png) 

##  IV. Python code 

Open3D hidden point removal 



--------------------------------------------------------------------------------

##  First, the principle of the algorithm 

###  1. Registration process 

  ICP iteratively corrects the rigid body transformation (translation, rotation) of the two original point clouds to minimize the distance between all point sets. Input: Two frames of original point clouds, initial estimate of the transformation, standard for stopping the iteration; Output: transformation matrix, modified point cloud after transformation. ICP algorithm steps: (1) For the point set 

(4) Determine whether the convergence is based on the two iteration errors before and after and the number of iterations. If it converges, output the final result: 

###  2. Algorithm derivation 

>  Description of ICP algorithm on PCL official website: How to use iterative closest pointICP algorithm detailed derivation process: 3D point cloud registration - ICP algorithm principle and derivation 

###  3. References 

>  [1] BESL P J, MCKAY N D. A method for registration of 3-Dshapes [J]. IEEE Transactions on Pattern Analysis and Machine Intelligence, 1992, 14 (2): 239-256. [2] Wang Fei, Liu Rufei, Ren Hongwei, Chai Yongning. Multi-phase vehicle laser point cloud registration using road target features [J]. Journal of Surveying and Mapping Science and Technology, 2020, 37 (05): 496-502. [3] Liu Rufei, Wang Fei, Ren Hongwei, Wang Minye, Yang Jiben. A road scene laser point cloud registration method using geographic entity target features [J/OL]. China Laser: 1-20 [2022-08-17]. http://kns.cnki.net/kcms/detail/31.1339.tn.20220714.1202.010.html 

###  4. Main functions 

1. This class TransformationEstimationPointToPoint provides functions for computing the residuals of the point-to-point ICP objective function and the Jacobian matrix. The function RegistrationICP takes this as a parameter and runs the point-to-point ICP to get the result. 

2. The function EvaluateRegistration compute the two main indicators. Fitness computes the overlapping area (interior correspondence/target number of points). The higher the better. inlier_rmse computes the root mean square error RMSE for all interior correspondence. The lower the better. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588688
 ```  
3, the function ICPConvergenceCriteria set some parameters of the ICP algorithm. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588688
 ```  
##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588688
 ```  
##  III. Display of results 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574588688
 ```  
###  1. Before registration 

![avatar]( bd1a1e7e95ac4d37b2f5df6844ba5302.png) 

###  2. After registration 

![avatar]( 473bf598c21a483ab19893a64c31a305.png) 

##  IV. Python code 

Open3D Point-to-Point ICP Registration Algorithm 



--------------------------------------------------------------------------------

##  I. Overview of algorithms 

![avatar]( 0f18892c85c84839a10493a835918bfe.jpeg) 

   The principle of the classical Kmeans algorithm is introduced in: PCL Kmeans point cloud clustering. Since the traditional Kmeans algorithm randomly selects the cluster center point, the clustering failure may occur. Therefore, the point selection strategy is improved, so that the probability of the algorithm success is greatly improved. As shown in the figure below, the traditional algorithm will divide the street lamp into two, and the improved classification is more accurate.  

##  Code implementation 

KMeans.h 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574590294
 ```  
KMeans.cpp 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574590294
 ```  
main.cpp 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574590294
 ```  
##  III. Display of results 

###  1. Primitive point cloud 

![avatar]( 7ef5c5f7ccde4170b5c959c71256557a.jpeg) 

###  2. Clustering results 

![avatar]( b9c249f6c6994709b789b13e0662dac9.jpeg) 



--------------------------------------------------------------------------------

##  I. Overview 

  Inserting multiple points equally spaced between two points is an important operational basis for encrypting point cloud boundaries and filling holes. 

##  Code implementation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574522113
 ```  
##  III. Display of results 

![avatar]( ff13bd13ca4743c8993ca19a43bc8a08.png) 

##  IV. Experimental data 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574522113
 ```  


--------------------------------------------------------------------------------

