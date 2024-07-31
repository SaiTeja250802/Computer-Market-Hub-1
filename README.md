# Sheet-Stack-Counter

This Streamlit application is designed to count the number of sheet stacks in a manufacturing plant using image processing techniques. The app allows users to upload an image of a sheet stack, process it to detect edges, and count the lines representing individual sheets. The application can either use custom parameters provided by the user or find the optimal parameters for line detection.



## Installation

* Install requirements with pip

```bash
  pip install streamlit opencv-python-headless numpy pillow

```

* Save the code in a Python file, e.g., final.py.

* Run the Streamlit application    

```bash
  streamlit run final.py

```

## Acknowledgments
 - [Streamlit](https://streamlit.io/)
 - [opencv](https://opencv.org/)
 - [pillow](https://pypi.org/project/pillow/)
 - [Numpy](https://numpy.org/)

## Features

- **Image Upload:** Users can upload images in JPG, JPEG, or PNG formats.
- **Image Resizing:** Uploaded images are resized to 256x256 pixels for consistent processing.
- **Edge Detection:** Converts the image to grayscale, applies Gaussian blur, and uses the Canny edge detection algorithm to identify edges.
- **Custom Parameters:** Users can toggle to use custom parameters for line detection including threshold, minimum line length, and maximum line gap.
- **Optimal Parameters:** The application can automatically find the best parameters for line detection to maximize the number of detected lines.
- **Line Detection and Counting:** Uses the Hough Line Transform to detect lines in the edge-detected image and counts the lines representing sheets.
- **Results Display:** Shows the original image, edge-detected image, and lines image side by side, along with the optimal parameters and the count of detected lines and sheets.


## Screenshots

![App Screenshot](https://github.com/SaiTeja250802/Computer-Market-Hub-1/blob/main/1.png)
![App Screenshot](https://github.com/SaiTeja250802/Computer-Market-Hub-1/blob/main/2.png)
![App Screenshot](https://github.com/SaiTeja250802/Computer-Market-Hub-1/blob/main/3.png)
![App Screenshot](https://github.com/SaiTeja250802/Computer-Market-Hub-1/blob/main/4.png)
![App Screenshot](https://github.com/SaiTeja250802/Computer-Market-Hub-1/blob/main/5.png)
![App Screenshot](https://github.com/SaiTeja250802/Computer-Market-Hub-1/blob/main/6.png)
![App Screenshot](https://github.com/SaiTeja250802/Computer-Market-Hub-1/blob/main/7.png)
