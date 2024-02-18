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

