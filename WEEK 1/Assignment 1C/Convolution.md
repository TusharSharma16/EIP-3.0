**Name**: `Tushar Sharma`                             **Email**: `ts16sharma@gmail.com`                                  **Batch Number**:`2`

# Convolution
In General terms, **Convolution** refers to the process of Conversion of Image into **2-Dimensional Feature Matrix** so that the features can be extracted and analysed. In Mathematical Terms, **Convolution** refers to the Combined Integration of two Functions and it shows how one function is dependent on other.THe General Formula for Convolution is:

![12](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/12.png)

---
In Intuitive Terms, The **Feature Detector/Kernel/Filter** (Matrix) is multiplied to the Input Image Matrix to obtain a larger values matrix (called **Feature Map/Convolved Feature/Activation Map**) where the Kernel is moved based on value specified by the User called **Stride**. Multiple Feature Maps are preserved as **Filters**, which are decided during the Training of the Neural Net based on the Features of the Input Image.The filter analyzes every aspect of image. For them, which we will call the “initial pixel”, it multiplies the valued pixel and values of surrounding pixels by the kernel value. Then it adds results, and the initial pixel is set to this final result value.For example:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![11](https://github.com/TusharSharma16/EIP-3.0/blob/master/WEEK%201/images/11.png)

1. The Input Image is 5x5 matrix
2. The Kernel size is 3x3 matrix
3. The Output matrix is obtained after 9 iterations
---
