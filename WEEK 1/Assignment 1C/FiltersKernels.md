**Name**: `Tushar Sharma`                             **Email**: `ts16sharma@gmail.com`       **Batch Number**:`2`
# Filters/Kernels

Filters/Kernels is a matrix which on multiplication with the Input image, processes a new Matrix known as Feature Map which is used to identify features of the image. the Filters/Kernels have parameters such as :

1. **Stride**: represents the movement of the Filter/Kernel![convSobel](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images//convSobel.gif)

   

2. **Padding**: represents the spacing after which the Kernel is sent to next line

   ![FjvuN](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/FjvuN.gif)

   ---

   **Extraction of Features by Kernels**:

   Feature Extraction is the major task of Kernels/Filters which decide the Filter on the Input Image. For Shape Detection in OpenCV, the features extraction for shapes is Hu Moments(Image Moments) which associates with 7 Feature Extraction.

   The Following are the Extraction Techniques by Kernels:

   1. **Extend**: resembles the extension of boundary, so that the image is processed smoothly.
   2. **wrap**: resembles the storing of values in a smaller form.
   3. **Mirror**: resembles the Mirrored Image movement of the image.
   4. **crop**: resembles the resizing of the image for specific features.
   5. **Kernel Crop**: resembles the normalisation of Kernel Size.

For example:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![11](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/11.png)

1. The Input Image is 5x5 matrix
2. The Kernel size is 3x3 matrix
3. The Output matrix is obtained after 9 iterations
---
Based on the Features, Filters are obtained based on the Kernel Matrix. For Examples:

**Sharpen Filter**: The Sharpen Kernel is Obtained based on the Kernel Features as illustrated below:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Matrix:&nbsp;![2](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/2.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The final image:&nbsp;![3](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/3.jpg)

**Blur Filter**: The Blur Kernel is Obtained based on the Kernel Features as illustrated below:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Matrix:&nbsp;![4](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/4.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Final image:&nbsp;![5](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/5.jpg)

**Edge Enhance Filter**:The Edge Enhance Kernel is Obtained based on the Kernel Features as illustrated below:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Matrix:&nbsp;![6](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/6.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Final image:&nbsp;![7](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/7.jpg)

**Edge Detect Filter**:The Edge Detection Kernel is obtained based on the Kernel Features as illustrated below:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Matrix:&nbsp;![8](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/8.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Final image:&nbsp;![9](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/9.jpg)

**Emboss Filter**:The Emboss Kernel is obtained based on the Kernel Features as illustrated below:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Matrix:&nbsp;![10](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/10.png)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Final image:&nbsp;![11](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/11.jpg)

---
