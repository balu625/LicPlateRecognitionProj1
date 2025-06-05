The Aim of this project to detect the license plate with the two stages 

In first stage we have
1. Training Set 1: This set comprises 900 images, with each image featuring a single car along with its corresponding license plate.
2. The provided annotations include the coordinates of the bounding box (ymin, xmin, ymax, xmax) that outlines the license plate in each image.

By using this training set and annotations including coordinates of bounding box gives the detection of plates

![image](https://github.com/user-attachments/assets/3cedb4bb-5b93-44b3-a325-383e6b76b943)

it gives the ouput inside the green box which is giving the number plate.

In second stage we have
2. Training Set 2: Consisting of another 900 images, this set focuses solely on license plates.
Each image in this set contains a license plate, and the provided annotations contain the characters present on each license plate.
By using the above training set we are gong to present the characters present on each license plate.

![image](https://github.com/user-attachments/assets/4083ba7f-2c9d-4305-87e4-4fb40007c12b)

With all these ouputs we conclude that we can find the number plates with the boundaries .
Now we are going to train the model to test whether our model work perfectly or not by test set and the theory given below.

3. Test Set: This set consists of 201 images and is structured similarly to the first training set.
In this set, your task is twofold: you need to detect the license plates within the images and recognize the characters on those plates. 

Finally , we have trained a model to find the license plate of a vehicle.
