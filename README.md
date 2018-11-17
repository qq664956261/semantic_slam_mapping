
# This is my graduation project.
=======
#This semantic mapping code is my graduation project


Some results
=======
![result1][1]   
![result2][6]
![result3][2]
![result4][3]
![result5][4]
![result6][5]

[1]: https://github.com/MuMuJun97/semantic_slam_mapping/blob/master/001.png
[2]: https://github.com/MuMuJun97/semantic_slam_mapping/blob/master/2.png
[3]: https://github.com/MuMuJun97/semantic_slam_mapping/blob/master/3.png
[4]: https://github.com/MuMuJun97/semantic_slam_mapping/blob/master/0002.png
[5]: https://github.com/MuMuJun97/semantic_slam_mapping/blob/master/0002.jpg
[6]: https://github.com/MuMuJun97/semantic_slam_mapping/blob/master/000000.png

Models
====
>- Models files are not here, you can choose to modify this file:

```
//segnet.cpp
    std::string model_file = "../models/segnet_model_driving_webdemo.prototxt";
    std::string trained_file = "../models/segnet_weights_driving_webdemo.caffemodel";
    std::string label_file = "../models/semantic12.txt";
```


> - [ ] The semantic segmentation methon is based on [Alex Kendall's work ](https://github.com/MuMuJun97/caffe-segnet) 

>- [ ] Caffe Segnet is a modified version of **Caffe** which supports the **SegNet** architecture

>- [ ] The mapping architecture is based on GaoXiang's work and **ORB-SLAM**.


----
Getting Started
=======
If you would like to try out this code , you should satisfy these requirements first.

#OpenCV
I choose to use OpenCV to manipulate images and features. Dowload and install instructions can be found at: http://opencv.org. Required at OpenCV 2.4.x.Note that my code is not compatible with OpenCV3.0

Eigen 3.0+
======

PCL 1.7
======

DBoW2(for loop closure) and g2o(for solving pnp)
=======

