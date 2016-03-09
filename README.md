# ImageStitching
image stitching algorithms from the internet

#Test Image Statement
images were photoed by iphone 5, using 4 images to test a algorithm

#1.TongJi-algorithm
web-page: http://sse.tongji.edu.cn/linzhang/CV14/Projects/panorama.htm
algorithm:
step1: Harris Corner Detection to get feature points
step2: local descriptor for each point: he used a fixed neighborhood as the descriptor
step3: using RANSAC algorithm to find the inliers of the correspondence pairs and to estimate the homography matrix
step4: using the estimated homography matrix to transform img1 to the coordinate system of img2
step5: merge
implemented in matlab
test result:
total time:  , final image: 

#2.FiJi
