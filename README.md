# Breast-Cancer-Detection-using-Image-Processing
This MATLAB script is designed for the detection of breast tumors in medical images, specifically focusing on breast cancer diagnosis. The project employs image processing techniques and a threshold-based classification approach to identify potential cancerous regions within the breast.

## Key Steps:
## 1. Image Loading:
Enables the user to select a JPEG image for analysis.
## 2. Preprocessing:
Converts the RGB image to grayscale.
Applies a median filter to reduce noise.
## 3. Thresholding:
Determines an optimal threshold to create a binary image.
## 4. Morphological Operations:
Performs morphological operations (closing) to enhance the binary image.
## 5. Region of Interest (ROI) Extraction:
Fills holes in the binary image to create the final ROI.
## 6. Feature Extraction:
Utilizes region properties (Area, Perimeter, Eccentricity, Solidity, Centroid) to characterize regions in the ROI
## 7. Classification:
Employs a simple threshold-based classification to identify potential cancerous regions.
## 8. Visualization:
Displays the original image and the identified ROI.
## Conclusion:
This MATLAB script provides a foundation for breast cancer detection in medical images. Leveraging image processing techniques and basic classification, it identifies potential cancerous regions, contributing to the ongoing efforts in medical image analysis for breast cancer diagnosis. Users are encouraged to explore and enhance this project for broader applications in the field of medical imaging.
