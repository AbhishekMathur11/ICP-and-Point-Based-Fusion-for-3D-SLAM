# ICP and Point Based Fusion for 3D SLAM

This project uses ICP and Point Based fusion for Lidar Visual Odometry done by a mobile robot inside a room. 

The initial super imposed scan from two separate frames looks like this:

![alt text](https://github.com/AbhishekMathur11/ICP-and-Point-Based-Fusion-for-3D-SLAM/blob/main/results/ICP_pre.png)

This has a lot of drift and error


After integrating ICP, the new scan looks like: 

![alt text](https://github.com/AbhishekMathur11/ICP-and-Point-Based-Fusion-for-3D-SLAM/blob/main/results/ICP_post.png)

Once point based fusion is applied to the system, the intial result without dense fusion is:

![alt text](https://github.com/AbhishekMathur11/ICP-and-Point-Based-Fusion-for-3D-SLAM/blob/main/results/Fusion.png)

After applying dense fusion, the final result:


![alt text](https://github.com/AbhishekMathur11/ICP-and-Point-Based-Fusion-for-3D-SLAM/blob/main/results/Dense.png)
