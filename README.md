# PAN Card Tampering Detection using Computer Vision

## Overview:
This project aims to develop a robust solution for detecting tampering in PAN (Permanent Account Number) cards using Computer Vision techniques. With the rise in identity fraud cases, especially involving forged or tampered identification documents, there is a growing need for advanced tools to verify the authenticity of such documents. Leveraging the power of Python and libraries like OpenCV, scikit-image, and imutils, this project demonstrates the feasibility of using image processing algorithms to detect tampering in PAN cards.

## Key Features:
1. **Image Retrieval:** The project includes functionality to scrape PAN card images from the web, simulating real-world scenarios where documents may be obtained from various sources.
2. **Image Preprocessing:** Uniform formatting of images ensures consistency in size and format, facilitating accurate comparison and analysis.
3. **Grayscale Conversion:** Images are converted to grayscale to simplify processing and retain essential details for analysis.
4. **SSIM Calculation:** The Structural Similarity Index (SSIM) is computed to quantify the similarity between original and tampered images, providing a metric for detecting discrepancies.
5. **Thresholding & Contour Detection:** Thresholding techniques are applied to create binary images, followed by contour detection to identify and outline discrepancies between images.
6. **Visualization:** The project includes functionality to visualize images with contours and differences, aiding in visual inspection and analysis of tampering.

## Usage:
1. **Environment Setup:** Ensure that the required Python libraries (OpenCV, scikit-image, imutils) are installed in the environment using the provided installation commands.
2. **Image Retrieval:** Modify the image URLs in the provided code to fetch original and tampered PAN card images from the web.
3. **Image Processing:** Execute the code to preprocess images, compute SSIM score, perform thresholding, and detect contours to identify tampering.
4. **Analysis & Visualization:** Analyze the output, including SSIM score, contour detection, and visual representations of original and tampered images with detected discrepancies.

## Conclusion & Future Scope:
This project demonstrates the effectiveness of Computer Vision techniques in detecting tampering in PAN cards, offering a valuable tool for organizations to enhance their fraud detection capabilities. Future enhancements could include the integration of machine learning algorithms for automated tampering detection and extending the solution to verify other types of identification documents like Aadhar cards, Voter IDs, etc. 

## Contributors:
- Amarjeet Singh Chauhan

## Contact Information:
For inquiries or collaborations related to this project, please contact [achauhan17012000@gmail.com].
