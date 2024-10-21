Purposal
==============

For our final project in the Computer Vision course at Sapienza University in 2024, we customized YOLOv8 models to get better at detecting objects. We organized our data carefully, used cutting-edge training methods like gradually increasing learning rates and adding variety to our data, and closely checked our results to really understand how well our object detection works.


**Dataset:**

![alt text](https://production-media.paperswithcode.com/datasets/CLEVR-Hans3.png)

The [CLEVR-Hans dataset](https://github.com/ml-research/CLEVR-Hans/tree/main) it can challenge object detection models with its variety of objects such as [cubes, spheres, and cylinders] and each have diffrence in attributes like color, size, and shape. 
In this dataset each classes have specific characteristics:
* the first class changes the color of a large grey cube during tests; 
* the second varies the material of a small metal sphere in the test set; 
* and the third class which is not confounded, includes a large blue and a small yellow sphere. 

This setup tests the model’s ability to correctly identify objects under varying conditions.
