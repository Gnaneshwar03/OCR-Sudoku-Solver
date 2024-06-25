# Image Sudoku Solver (OCR Based)

This project implements a Sudoku solver that takes an image of a Sudoku puzzle as input and returns the solved puzzle overlaid on the original image.

## Sample Image

![image](https://github.com/Gnaneshwar03/OCR-Sudoku-Solver/assets/107243397/2a490a73-33ae-4bfe-8cef-6e58ea1c48e7)

## Features

- Image processing to extract the Sudoku grid
- Digit recognition using a trained convolutional neural network
- Sudoku solving algorithm
- Solution overlay on the original image

## Requirements

- Python 3.x
- OpenCV
- NumPy
- TensorFlow / Keras
- SciPy

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/Gnaneshwar03/OCR-Sudoku-Solver
   ```

2. Install the required packages:
   ```
   pip install opencv-python numpy tensorflow scipy
   ```

## Usage

1. Modify the `image_path` variable in the main script to point to your image:
   ```python
   image_path = "path/to/your/sudoku/image.jpg"
   ```

2. Run the script:
   Run all the blocks of the ipynb file. The last block executes all the processes in the pipeline and gives out the solved sudoku.

## How It Works

1. **Image Processing**: The input image is processed to extract the Sudoku grid.
2. **Digit Recognition**: A CNN model recognizes the digits in each cell of the grid.
3. **Sudoku Solving**: The extracted puzzle is solved using a backtracking algorithm.
4. **Solution Overlay**: The solution is overlaid on the original image.
