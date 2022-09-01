# Write-on-air
Computer vision project implemented with OpenCV

Ever desired to draw your creativeness by way of simply waiving your finger in air. In this put up we will discover ways to build an Air Canvas which can draw something on it with the aid of just shooting the movement of a coloured marker with camera. Here a colored object at tip of finger is used as the marker.

We may be the use of the computer vision techniques of OpenCV to construct this assignment. The preferred language is python because of its exhaustive libraries and smooth-to-use syntax but know-how the fundamentals it is able to be applied in any OpenCV-supported language.

Here Colour Detection and monitoring are used for you to gain the objective. The color marker is detected and a mask is produced. It includes the further steps of morphological operations on the masks produced which are Erosion and Dilation. Erosion reduces the impurities gift in the mask and dilation in addition restores the eroded essential mask.

# Objective of the work

The motto of our Air Canvas undertaking is living within the have an effect on of using a simplified form of model-based totally approach, for favouring in addition changes some distance greater effortlessly. We proposed this air canvas set of rules supported with the aid of landmark alignment underneath the substitute framework. Further beneficial factors consist of virtual drawing, writing notes, meeting explanations and in addition destiny upgrades as covered.

# Technologies Used

The Air Canvas is built on the following technologies:
* [Python](https://www.python.org/) : Interpreted high-level general-purpose programming language for programming and development.
* [OpenCv](https://opencv.org/) : Open Source library of python with programming functions mainly aimed at real-time computer vision.
* [NumPy](https://numpy.org/) : Library of Python, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

# Algorithmic Approach
* [Step 1]: Start reading the frames and convert the captured frames to HSV color space (Easy for color detection).
* [Step 2]: Prepare the canvas frame and put the respective ink buttons on it.
* [Step 3]: Adjust the track bar values for finding the mask of the colored marker.
* [Step 4]: Preprocess the mask with morphological operations (Eroding and dilation).
* [Step 5]: Detect the contours, find the center coordinates of the largest contour and keep storing them in the array for successive frames (Arrays for drawing points on canvas).
* [Step 6]: Finally draw the points stored in an array on the frames and canvas.
