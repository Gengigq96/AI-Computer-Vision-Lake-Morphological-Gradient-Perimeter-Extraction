# Lake Perimeter Extraction during Drought using Morphological Gradient

## Objectives

This project aims to extract the perimeter of a lake during a drought period (after 4 years) from satellite images using **morphological gradient calculations**. The goal is to explore image processing techniques and apply them to satellite imagery to study changes in the lake's perimeter over time, especially in drought conditions.

### Key Goals:
- Understand the concept of **morphological gradient** in image processing.
- Extract and analyze the **lake perimeter** from satellite images using the morphological gradient technique.
- Compare satellite images from two different years to study the impact of drought on the lake perimeter.
- Implement and apply image processing algorithms to detect and highlight the changes in the shape of the lake.

## Dataset Description

This project uses **satellite images** that show the lake's condition over two different periods. The first image is from a time when the lake had its normal water levels, and the second image is after 4 years of drought. The objective is to measure how the perimeter of the lake has changed over this time by extracting the boundary from both images.

You will work with **grayscale** satellite images, as these are easier to process for morphological operations.

### Tasks to be Completed

1. **Image Preprocessing**:
   - Load and preprocess the satellite images to prepare them for morphological gradient calculation.
   - Convert the images to grayscale if necessary, and apply any required image enhancements to improve edge detection.
   
2. **Morphological Gradient Calculation**:
   - Implement the morphological gradient operation to highlight the edges of the lake perimeter.
   - Apply morphological operations such as dilation and erosion to compute the gradient and extract the boundary of the lake.

3. **Perimeter Extraction**:
   - Use contour detection to calculate the **lake perimeter** after applying the morphological gradient.
   - Compare the extracted perimeters from both images and analyze the changes in the lake’s boundary.

4. **Visualization and Analysis**:
   - Visualize the extracted lake perimeter on the original satellite images to show the difference in size due to drought.
   - Quantify the changes by calculating the difference in perimeter between the two images.

### Example of Morphological Gradient in Image Processing

The morphological gradient is calculated as the difference between the dilation and erosion of an image. It highlights the boundaries of objects (in this case, the lake) and can be used to extract contours and edges.

The formula for the morphological gradient is:
\[
\text{Gradient}(I) = \text{Dilate}(I) - \text{Erode}(I)
\]
Where:
- **Dilate** expands the bright regions of the image.
- **Erode** shrinks the bright regions of the image.
  ![image](https://github.com/user-attachments/assets/73c87c4b-5254-40a4-9278-f4ac1b61beec)


