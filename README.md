# ImageStitching
image stitching algorithms from the internet
===============

##Test Image Statement
images were photoed by iphone 5, using 4 images to test a algorithm<br>
the image is shown as follow:<br>
![](https://github.com/JeremyJiWZ/ImageStitching/raw/master/images/test1.jpg)
![](https://github.com/JeremyJiWZ/ImageStitching/raw/master/images/test2.jpg)
![](https://github.com/JeremyJiWZ/ImageStitching/raw/master/images/test3.jpg)
![](https://github.com/JeremyJiWZ/ImageStitching/raw/master/images/test4.jpg)

##1.TongJi-algorithm
web-page: http://sse.tongji.edu.cn/linzhang/CV14/Projects/panorama.htm<br>
algorithm:<br>
step1: Harris Corner Detection to get feature points<br>
step2: local descriptor for each point: he used a fixed neighborhood as the descriptor<br>
step3: using RANSAC algorithm to find the inliers of the correspondence pairs and to estimate the homography matrix<br>
step4: using the estimated homography matrix to transform img1 to the coordinate system of img2<br>
step5: merge<br>
implemented in matlab<br>
total time: 33.591s ,<br>
final image: <br>
`It just doesn't work on these input images`<br>
![](https://github.com/JeremyJiWZ/ImageStitching/raw/master/tongji/result.png)

##2.FiJi

implemented in java<br>
test result:<br>
total time:  , final image: <br>


##3.bolismauro
web-page: https://github.com/bolismauro/Panorama-creator<br>
algorithm overview: A Matlab Image stitching implementation using SIFT and RANSAC.<br>
implemented in matlab<br>
total time: 86.737s ,<br>
final image: <br>
`It just doesn't work on these input images`<br>
![](https://github.com/JeremyJiWZ/ImageStitching/raw/master/Panorama-creator-master/result.png)


##4.Open-CV standard stitching
just use open-cv image stitching algorithm to stitch images<br>
implemented in c++.<br>
total time: 2335ms,<br>
final image: ![](https://github.com/JeremyJiWZ/ImageStitching/raw/master/PanoStitch/panoResult.jpg)<br>

