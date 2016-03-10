# ImageStitching
image stitching algorithms from the internet

##Test Image Statement
images were photoed by iphone 5, using 4 images to test a algorithm

##1.TongJi-algorithm
web-page: http://sse.tongji.edu.cn/linzhang/CV14/Projects/panorama.htm<br>
algorithm:<br>
step1: Harris Corner Detection to get feature points<br>
step2: local descriptor for each point: he used a fixed neighborhood as the descriptor<br>
step3: using RANSAC algorithm to find the inliers of the correspondence pairs and to estimate the homography matrix<br>
step4: using the estimated homography matrix to transform img1 to the coordinate system of img2<br>
step5: merge<br>
implemented in matlab<br>
test result:<br>
total time:  , final image: <br>

##2.FiJi

implemented in java<br>
test result:<br>
total time:  , final image: <br>


##3.bolismauro
web-page: https://github.com/bolismauro/Panorama-creator<br>
algorithm overview: A Matlab Image stitching implementation using SIFT and RANSAC.<br>
implemented in matlab<br>
test result:<br>
total time:  , final image: <br>

##4.Open-CV standard stitching
just use open-cv image stitching algorithm to stitch images<br>
source code: https://github.com/prateekvjoshi/PanoStitch<br>
implemented in c++.<br>
total time: , final image: <br>

