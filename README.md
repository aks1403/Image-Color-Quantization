# Image Compression using KMeans Clustering

## Objective
Develop an image compression model using KMeans clustering to reduce color diversity while preserving visual quality.

## Approach

1. **Data Transformation:**
   - Import the image as a 3D array.
   - Convert it to a 2D array for pixel-wise analysis.

2. **Dataset Preparation:**
   - Create a dataset with RGB values from the 2D array.

3. **KMeans Clustering:**
   - Choose the desired color count.
   - Apply KMeans to predict clusters for each pixel.

4. **Color Reduction:**
   - Assign each pixel to its cluster's centroid, reducing color diversity.
   - Update the 2D array with new RGB values.

5. **Conversion and Export:**
   - Convert the modified 2D array back to a 3D array.
   - Export the compressed image.

## Results
The project successfully compressed images, maintaining essential features by capturing dominant color palettes through KMeans clustering. It demonstrates expertise in image processing, machine learning, and practical algorithm implementation.


## Dependencies
- NumPy
- Matplotlib
- Scikit Learn

## Author
Aditya Kumar Singh
