# Digital Image Processing
<img align="left" alt="Image" src="https://images.unsplash.com/photo-1526374965328-7f61d4dc18c5?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=870&q=80" width="1000" height="400" />

Here we can see some of the projects I have done during my Digital Image Processing course <br /> spring 2021

## 🔖 Homework 1 
- Goal: Find the best filter to eemove the image noise 
- Applying the listed filters on the image to see what will happen: 
       1. Averaging filter
       2. Median filter
       3. Laplacian filter
- performing power-law transformation on the image
- As expected ,The Median filtered output image was the best result.
- Generally , Median filterscan be a good choice for reducing salt or pepper noise on the image
- We can see That salt noise is removed,and the image is much brighter after using Median filter

![Figure_1](https://user-images.githubusercontent.com/88426435/137598918-c16b2a50-b8be-4e08-92c9-49d6df3acf1a.png)

## 🔖 Homework 2
- Goal: Motion detection while comparing three images taken by NASA
- Applying bit plane slicing
- Motion detection
- Bit plane slicing on the image of an electrical board

![Figure_1](https://user-images.githubusercontent.com/88426435/137601504-946d66dd-d9ca-4b55-9721-adbd1a2406ae.png)

- Motion Detection : We compared 3 images with the help of their mostsignificate planes extracted through Bit plane slicing 
- As we can see the difference of image NASA_B and NASA_C includes more white points, So the object movement was more considerable 

![Figure_1](https://user-images.githubusercontent.com/88426435/137601630-1986f440-2a9f-43c2-8654-723d86adb999.png)

## 🔖 Homework 3
- Goal: Detect Cells in this biomedical image by applying a circle detection algorithm
- Applying Canny filter to find the best parameters that can detect the borders of circles
- Use those parameters in Hough circle transformation

![Figure_1](https://user-images.githubusercontent.com/88426435/137601796-24f09b47-7332-44df-8b42-f9bf4fa11115.png)

## 🔖 Homework 4
- Goal: Reconstruct the original image from the transformed image
- Choose three landmarks 
- Find the affine transformation matrix to reconstruct the original image

![2](https://user-images.githubusercontent.com/88426435/137602162-32152f6c-5339-4b01-a93e-2f81f6460609.png)

![Figure_1](https://user-images.githubusercontent.com/88426435/137602192-0ce64e2d-3502-4422-a47f-8fcae918faaf.png)

