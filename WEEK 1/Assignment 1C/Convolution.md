**Name**: `Tushar Sharma`                             **Email**: `ts16sharma@gmail.com`                                  **Batch Number**:`2`

# Convolution
In General terms, **Convolution** refers to the process of Conversion of Image into **2-Dimensional Feature Matrix** so that the features can be extracted and analysed. In Mathematical Terms, **Convolution** refers to the Combined Integration of two Functions and it shows how one function is dependent on other.THe General Formula for Convolution is:

![12](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/12.png)

---
In Intuitive Terms, The **Feature Detector/Kernel/Filter** (Matrix) is multiplied to the Input Image Matrix to obtain a larger values matrix (called **Feature Map/Convolved Feature/Activation Map**) where the Kernel is moved based on value specified by the User called **Stride**. Multiple Feature Maps are preserved as **Filters**, which are decided during the Training of the Neural Net based on the Features of the Input Image.The filter studies successively every pixel of the image. For each of them, which we will call the “initial pixel”, it multiplies the value of this pixel and values of the surrounding pixels by the kernel corresponding value. Then it adds the results, and the initial pixel is set to this final result value.For example:

![11](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/11.png)

1. The Input Image is 5x5 matrix
2. The Kernel size is 3x3 matrix
3. The Output matrix is obtained after 9 iterations
---
Based on the Features, Filters are obtained based on the Kernel Matrix. For Examples:

**Sharpen Filter**: The Sharpen Kernel is Obtained based on the Kernel Features as illustrated below:

Matrix:<br>![2](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/2.png)<br>The final image:<br>![3](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/3.jpg)

**Blur Filter**: The Blur Kernel is Obtained based on the Kernel Features as illustrated below:

Matrix:![4](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/4.png)                                  The Final image:![5](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/5.jpg)

**Edge Enhance Filter**:The Edge Enhance Kernel is Obtained based on the Kernel Features as illustrated below:

Matrix:![6](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/6.png)
The Final image:![7](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/7.jpg)

**Edge Detect Filter**:The Edge Detection Kernel is obtained based on the Kernel Features as illustrated below:

Matrix:![8](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/8.png)
The Final image:![9](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/9.jpg)

**Emboss Filter**:The Emboss Kernel is obtained based on the Kernel Features as illustrated below:

Matrix:![10](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/10.png)
The Final image:![11](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/11.jpg)

---

