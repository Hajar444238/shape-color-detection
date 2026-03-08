# shape-color-detection
This project implements a shape and color detection system using Python and OpenCV. It processes images to detect geometric shapes such as triangles, squares, rectangles, circles, and pentagons, then identifies their colors by analyzing RGB values and matching them with CSS3 color names. It demonstrates basic computer vision techniques.


# Shape and Color Detection using OpenCV

This project implements a shape and color detection system using Python and OpenCV. The program analyzes an image to detect geometric shapes and identify their corresponding colors.

## Features

- Detection of geometric shapes (triangle, square, rectangle, pentagon, circle)
- Color detection based on RGB values
- Matching detected colors with CSS3 color names
- Contour detection and image processing
- Labeling shapes and colors directly on the image

## Technologies Used

- Python
- OpenCV
- NumPy
- SciPy
- imutils
- webcolors

## How it Works

1. The image is resized for faster processing.
2. It is converted to grayscale and blurred to reduce noise.
3. A binary threshold is applied to separate objects from the background.
4. Contours are detected using OpenCV.
5. Each contour is analyzed to determine the shape.
6. The average color inside the shape is computed.
7. The RGB value is matched to the closest CSS3 color name.
8. The shape and color label are displayed on the image.

## Project Structure
