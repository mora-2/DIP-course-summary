# Outline of Digital Image Processing (2023V2)  

## Chapter 1

| Concept          | Formula or filter mask | Algorithm Step | Application | Programming                            |
| ---------------- | ---------------------- | -------------- | ----------- | -------------------------------------- |
| Image            |                        |                |             |                                        |
| Digital Image    |                        |                |             | <a href="###Digital Image">Yes</a>     |
| Pixel            |                        |                |             |                                        |
| Image Resolution |                        |                |             | <a href="###Image Resolution"> Yes</a> |

## Chapter 2

| Concept                              | Formula or filter mask                                  | Algorithm Step | Application | Programming                                     |
| :----------------------------------- | :------------------------------------------------------ | -------------- | ----------- | ----------------------------------------------- |
| Image Formation Model                | <a href="###Image Formation Model">Yes</a>              |                |             |                                                 |
| Spatial Resolution                   | <a href="###Spatial Resolution">Yes</a>                 |                |             |                                                 |
| Intensity Resolution                 |                                                         |                |             |                                                 |
| 4-Neighbors                          | <a href="###Neighbors">Yes</a>                          |                |             | Yes                                             |
| D-Neighbors                          | <a href="###Neighbors">Yes</a>                          |                |             | Yes                                             |
| 8-Neighbors                          | <a href="###Neighbors">Yes</a>                          |                |             | Yes                                             |
| 4-adjacency                          |                                                         |                |             |                                                 |
| 8-adjacency                          |                                                         |                |             |                                                 |
|                                      |                                                         |                |             |                                                 |
| Digital Path                         |                                                         |                |             |                                                 |
| Closed Digital Path                  |                                                         |                |             |                                                 |
| Foreground & Background              | <a href="###Foreground & Background">Yes</a>            |                |             |                                                 |
| Inner Border                         | <a href="###Inner Border">Yes</a>                       |                |             | Yes                                             |
| Outer Border                         | <a href="###Outer Border">Yes</a>                       |                |             | Yes                                             |
| Euclidean distance                   | <a href="####Euclidean distance">Yes</a>                |                |             | Yes                                             |
| City-block distance                  | <a href="####City-block distance">Yes</a>               |                |             | Yes                                             |
| Chessboard distance                  | <a href="####Chessboard distance">Yes</a>               |                |             | Yes                                             |
| Arithmetic Operation: Addition       | Yes                                                     |                | Yes         | Yes                                             |
| Arithmetic Operation: Subtraction    | Yes                                                     |                | Yes         | Yes                                             |
| Arithmetic Operation: Multiplication | Yes                                                     |                | Yes         | Yes                                             |
| Arithmetic Operation: Div            | Yes                                                     |                | Yes         | Yes                                             |
| Averaging K different noisy images   | <a href="###Averaging K different noisy images">Yes</a> |                | Yes         |                                                 |
| Mix Operation                        | Yes                                                     |                | Yes         | Yes                                             |
| Single pixel operation               | <a href="###Single pixel operation">Yes</a>             |                |             |                                                 |
| Neighborhood operation               | <a href="###Neighborhood operation">Yes</a>             |                |             |                                                 |
| Spatial Transform                    |                                                         |                |             |                                                 |
| Forward Mapping                      | <a href="###Forward & Backward Mapping">Yes</a>         |                |             |                                                 |
| Inverse Mapping                      | <a href="###Forward & Backward Mapping">Yes</a>         |                | Yes         | <a href="###Inverse Mapping"> Yes</a>           |
| Affine Transform                     | <a href="#AF"> Yes</a>                                  |                |             | <a href="###Affine Transform">Yes (Matrix)</a>  |
| Scaling Transform                    | Yes                                                     |                |             | Yes                                             |
| Rotation Transform                   | Yes                                                     |                |             | Yes                                             |
| Translation Transform                | Yes                                                     |                |             | Yes                                             |
| Flip H Transform                     | Yes                                                     |                |             | Yes                                             |
| Flip V Transform                     | Yes                                                     |                |             | Yes                                             |
| Composted Affine Transform           | Yes                                                     |                | Yes         | <a href="###Composted Affine Transform">Yes</a> |
| Nearest Neighborhood Interpolation   | <a href="###Nearest Neighborhood Interpolation">Yes</a> |                | Yes         | Yes                                             |
| Bilinear Interpolation               | <a href="###Bilinear Interpolation">Yes</a>             |                | Yes         | Yes                                             |
|                                      |                                                         |                |             |                                                 |

## Chapter 3

| Concept                               | Formula or filter mask                     | Algorithm Step                              | Application                                                | Programming                                     |
| ------------------------------------- | ------------------------------------------ | ------------------------------------------- | ---------------------------------------------------------- | ----------------------------------------------- |
| Intensity Transform                   | <a href="###Intensity Transform">Yes</a>   |                                             |                                                            | Yes                                             |
| Spatial Filtering                     | <a href="###Spatial Filtering">Yes</a>     |                                             |                                                            | Yes                                             |
| Image Enhancement                     |                                            |                                             |                                                            |                                                 |
| Image Negative                        | <a href="###Image Negative">Yes</a>        |                                             |                                                            | yes                                             |
| Gamma Transformations                 | <a href="###Gamma Transformations">Yes</a> |                                             | yes                                                        | <a href="###Gamma Transformations-code">Yes</a> |
| Contrast stretching                   | <a href="###Contrast stretching">Yes</a>   |                                             |                                                            | Yes                                             |
| Thresholding                          | <a href="###Thresholding">Yes</a>          |                                             |                                                            | yes                                             |
|                                       |                                            |                                             |                                                            |                                                 |
| Brightness Transformation             | Yes                                        |                                             |                                                            | <a href="###Brightness Transformation">Yes</a>  |
| Histogram                             | <a href="###Histogram">Yes</a>             |                                             |                                                            | Yes                                             |
| Histogram Equalization                |                                            | <a href="###Histogram Equalization">Yes</a> | yes                                                        | yes                                             |
| Average Blur                          | <a href="###Average Blur">Yes</a>          |                                             | yes                                                        | <a href="###Average Blur-code">Yes</a>          |
| Gaussian Blur                         | <a href="###Gaussian Blur">Yes</a>         |                                             | yes                                                        | yes                                             |
| Salt and pepper noise                 |                                            |                                             |                                                            |                                                 |
| Median Filter                         |                                            | <a href="###Median Filter">Yes</a>          | yes                                                        | yes                                             |
| Laplacian                             | <a href="###Laplacian">Yes</a>             |                                             | yes                                                        | yes                                             |
| Sharpening Filter                     | <a href="###Sharpening Filter">Yes</a>     |                                             | yes                                                        | yes                                             |
| Unsharp Masking                       | <a href="###Unsharp Masking">Yes</a>       | yes                                         | yes                                                        | <a href="###Unsharp Masking-code">Yes</a>       |
| Gradient                              | Yes                                        |                                             |                                                            | yes                                             |
| Magnitude of Gradient                 | <a href="###Magnitude of Gradient">Yes</a> |                                             |                                                            | Yes                                             |
| Direction of Gradient                 | <a href="###Direction of Gradient">Yes</a> |                                             |                                                            | yes                                             |
| Sobel Mask                            | <a href="###Sobel Mask">Yes</a>            |                                             |                                                            | yes                                             |
| Combining Spatial Enhancement Methods |                                            |                                             | <a href="###Combining Spatial Enhancement Methods">Yes</a> |                                                 |
|                                       |                                            |                                             |                                                            |                                                 |

## Chapter 4/5

| Concept                           | Formula or filter mask                                 | Algorithm Step                 | Application | Programming                                                  |
| --------------------------------- | ------------------------------------------------------ | ------------------------------ | ----------- | ------------------------------------------------------------ |
| 2D-DFT                            |                                                        |                                |             |                                                              |
| 2D-IDFT                           |                                                        |                                |             |                                                              |
| FFT Shift                         |                                                        | <a href="###FFT Shift">Yes</a> |             | yes                                                          |
| Separability of 2D-DFT            |                                                        |                                | yes         |                                                              |
| Filtering in the Frequency Domain | <a href="###Filtering in the Frequency Domain">Yes</a> | yes                            |             |                                                              |
| Homomorphic Filtering             |                                                        | yes                            | yes         |                                                              |
| Low pass/High pass                | <a href="###Low pass/High pass">_ </a>                 |                                |             | <a href="###Low pass/High pass-code">Yes</a>(Create filter H) |
| Band reject                       | <a href="###Band reject">Yes</a>                       |                                | Yes         | <a href="###Band reject-code">Yes</a>                        |
| Notch Reject                      | <a href="###Notch Reject">Yes</a>                      |                                | yes         | Yes                                                          |
| Band pass                         | Yes                                                    |                                |             | Yes                                                          |
| Notch pass                        | Yes                                                    |                                |             | Yes                                                          |
|                                   |                                                        |                                |             |                                                              |
| Inverse Filtering                 | <a href="###Inverse Filtering">Yes</a>                 |                                |             |                                                              |
|                                   |                                                        |                                |             |                                                              |

## Chapter 6

| Concept                                                      | Formula or filter mask                                   | Algorithm Step                                              | Application | Programming                                        |
| ------------------------------------------------------------ | -------------------------------------------------------- | ----------------------------------------------------------- | ----------- | -------------------------------------------------- |
| RGB Model                                                    | Yes                                                      |                                                             | Yes         | <a href="###RGB Model">Yes</a>                     |
| HSI Model                                                    | <a href="###HSI Model">Formula of I(R,G,B)  S(R,G,B)</a> |                                                             | Yes         |                                                    |
| HSV Model                                                    | <a href="###HSI Model">Formula of V(R,G,B)  S(R,G,B)</a> |                                                             |             |                                                    |
| Pseudo color Image Processing                                |                                                          |                                                             | Yes         | <a href="###Pseudo color Image Processing">Yes</a> |
| Full Color Image processing  (RGB) Model                     |                                                          |                                                             | Yes         | <a href="###Full Color Image processing">Yes</a>   |
| Full Color Image Processing (HIS/HSV)   <br />Brightness Channel Processing  <br />Saturation Channel Processing |                                                          | <a href="###Full Color Image Processing (HIS/HSV) ">Yes</a> | Yes         |                                                    |
| Color Matrix  <br />1.    RGB =>Gray  <br />2.    Brightness Adjust  <br />3.    Saturation Adjust  <br />4.   Color Balance | <a href="###Color Matrix ">Yes</a>                       |                                                             | Yes         | <a href="###Color Matrix-code">Yes</a>             |

## Chapter 9

| Concept  | Formula or filter mask              | Algorithm Step | Application | Programming                             |
| -------- | ----------------------------------- | -------------- | ----------- | --------------------------------------- |
| Erosion  | <a href="###Erosion">Yes</a>        |                | Yes         | <a href="###Erosion & Dilation">Yes</a> |
| Dilation | <a href="###Dilation">Yes</a>       |                | Yes         | <a href="###Erosion & Dilation">Yes</a> |
| Open     | <a href="###Open and close">Yes</a> |                | Yes         | <a href="###Erosion & Dilation">Yes</a> |
| Close    | Yes                                 |                | Yes         | Yes                                     |
|          |                                     |                |             |                                         |

## Chapter 10

| Concept                        | Formula or filter mask                           | Algorithm Step                                    | Application | Programming                                           |
| ------------------------------ | ------------------------------------------------ | ------------------------------------------------- | ----------- | ----------------------------------------------------- |
| Image Segmentation             |                                                  |                                                   |             |                                                       |
| Detection of Isolated Point    | <a href="###Detection of Isolated Point">Yes</a> |                                                   |             | <a href="###Detection of Isolated Point-code">Yes</a> |
| Line Detection                 | <a href="###Line Detection">Yes</a>              |                                                   |             |                                                       |
| Edge Models                    |                                                  |                                                   |             |                                                       |
| Image gradient                 | <a href="###Image gradient">Yes</a>              |                                                   |             | yes                                                   |
| Magnitude of gradient vector   | <a href="###Image gradient">Yes</a>              |                                                   |             | Yes                                                   |
| Direction of gradient vector   | <a href="###Image gradient">Yes</a>              |                                                   |             | Yes                                                   |
| Gradient operator (basic)      | <a href="###Gradient operators">Yes</a>          |                                                   |             | Yes                                                   |
|                                |                                                  |                                                   |             |                                                       |
| Prewitt operator               | <a href="###Gradient operators">Yes</a>          |                                                   |             | Yes                                                   |
| Sobel operator                 | <a href="###Gradient operators">Yes</a>          |                                                   |             | Yes                                                   |
| Edge detection (thresholding)  |                                                  | Yes                                               |             | Yes                                                   |
| Edge detection (zero crossing) |                                                  | Yes                                               |             | Yes                                                   |
| Marr-Hildreth edge detector    |                                                  | <a href="###Marr-Hildreth edge detector">Yes</a>  |             | <a href="###Marr-Hildreth edge detector-code">Yes</a> |
| Canny edge detector            |                                                  | <a href="###Canny edge detector">Yes</a>          |             |                                                       |
| Intensity   thresholding       | <a href="###Intensity   thresholding">Yes</a>    |                                                   |             | Yes                                                   |
| Basic Global Thresholding      |                                                  | <a href="###Basic Global Thresholding">Yes</a>    |             |                                                       |
| Connected-component labeling   |                                                  | <a href="###Connected-component labeling">Yes</a> | yes         | Yes                                                   |
|                                |                                                  |                                                   |             |                                                       |

## Chapter 11

| Concept                            | Formula or filter mask               | Algorithm Step | Application | Programming |
| ---------------------------------- | ------------------------------------ | -------------- | ----------- | ----------- |
| Hough Transform (Line Detection)   | <a href="###Hough Transform">Yes</a> | Yes            | Yes         | Yes         |
| Hough Transform (Circle Detection) | <a href="###Hough Transform">Yes</a> | Yes            | Yes         |             |



## Formula

### Forward & Backward Mapping

Forward mapping and inverse mapping are concepts commonly used in computer graphics, computer vision, and image processing. They refer to different approaches for transforming points or pixels from one coordinate system to another.

1. **Forward Mapping:**
   - **Definition:** Forward mapping involves applying a transformation directly to the input points or pixels and determining their positions in the output space.
   - **Process:** Each point in the input space is transformed using the mapping function, and its corresponding location in the output space is computed. The transformation is applied from the source to the destination.
   - **Application:** Commonly used in computer graphics for tasks like geometric transformations, where the goal is to determine the positions of transformed points in the final image.

2. **Inverse Mapping:**
   - **Definition:** Inverse mapping involves finding the inverse transformation that maps points from the output space back to the input space.
   - **Process:** Each point in the output space is transformed using the inverse mapping function to determine its corresponding location in the input space. The transformation is applied from the destination back to the source.
   - **Application:** Useful when you know the desired location of points in the output space and want to find their corresponding positions in the input space. Commonly used in tasks like image registration, where the goal is to align two images.

**Example: Geometric Transformation (Translation) - Forward vs Inverse Mapping:**

Consider a 2D translation transformation where `(x', y')` is the translated point, and `(x, y)` is the original point. The transformation equations are:

- Forward Mapping:
  ```
  x' = x + dx
  y' = y + dy
  ```
  This directly gives the new coordinates in the output space.

- Inverse Mapping:
  ```
  x = x' - dx
  y = y' - dy
  ```
  This is used when you know the desired coordinates in the output space and want to find the corresponding coordinates in the input space.

In summary, the choice between forward mapping and inverse mapping depends on the problem at hand and whether you have information about the input or output space. Forward mapping is often used for transforming input points to output points, while inverse mapping is useful when you have information in the output space and want to find the corresponding points in the input space.

### Image Formation Model

![image-20231218154235421](.\images\image-20231218154235421.png)

![image-20231218154312146](.\images\image-20231218154312146.png)

### Spatial Resolution

Spatial resolution is a measure of the level of detail or granularity in an image, often expressed in terms of dots per inch (DPI), pixels per inch (PPI), lines per inch (LPI), or other similar units. Here's a brief explanation of these terms:

1. **Dots per Inch (DPI):**
   - DPI is a measure of the printing resolution of an image or a printer.
   - It represents the number of ink dots a printer can place within a one-inch square.
   - Higher DPI values generally result in higher print quality with finer details.

2. **Pixels per Inch (PPI):**
   - PPI is commonly used in the context of digital images and displays, such as computer monitors, cameras, and screens.
   - It represents the number of pixels within a one-inch square on a digital display.
   - Higher PPI values usually result in a sharper and more detailed image on a digital screen.

3. **Lines per Inch (LPI):**
   - LPI is often used in the context of halftone printing, such as in newspapers or magazines.
   - It represents the number of lines of dots that can be printed within one inch.
   - Higher LPI values generally result in smoother gradients and better reproduction of continuous tones.

The relationship between these terms can be summarized as follows:

- For digital displays (monitors, screens): PPI is the relevant measure.
- For printed materials (images, photographs): DPI is the relevant measure.
- In halftone printing: LPI is used to describe the resolution of the printed image.

In the context of spatial resolution, higher values indicate a finer level of detail, while lower values indicate less detail. The appropriate resolution depends on the specific application and the desired quality of the output. High spatial resolution is crucial for tasks such as photo editing or printing high-quality images, while lower resolution may be sufficient for general viewing on digital screens.

### Neighbors

<img src=".\images\image-20231218155440012.png" alt="image-20231218155440012" style="zoom:50%;" />

<img src=".\images\image-20231218155509958.png" alt="image-20231218155509958" style="zoom:50%;" />

<img src=".\images\image-20231218155523459.png" alt="image-20231218155523459" style="zoom:50%;" />

### Foreground & Background

![image-20231218160809452](.\images\image-20231218160809452.png)

### Inner Border

#### m-Adjacency

<img src=".\images\image-20231218162003312.png" alt="image-20231218162003312" style="zoom:50%;" />

**Bool Is_m_adjacent(byte[,]f, int px,int py,int qx,int qy);**

![image-20231218161926401](.\images\image-20231218161926401.png)

### Outer Border

![image-20231218164253702](.\images\image-20231218164253702.png)

### Distance

#### Euclidean distance 

![image-20231218164614644](.\images\image-20231218164614644.png)

#### City-block distance

The city-block distance, also known as the Manhattan distance or L₁ distance, is a measure of the distance between two points in a grid-based system (like a city grid) calculated by the sum of the absolute differences of their coordinates. It is named "city-block" because it measures the distance a taxi would travel in a city with a grid layout, where you can only move along streets that form a grid.

For two points \((x_1, y_1)\) and \((x_2, y_2)\), the city-block distance \(d\) is calculated as:

$$
d = |x_1 - x_2| + |y_1 - y_2|
$$
This distance is the sum of the absolute differences in the x-coordinates and y-coordinates. It doesn't take into account diagonal movement; you can only move horizontally or vertically.

Graphically, this corresponds to the length of the shortest path between two points that follows the grid lines, moving only horizontally or vertically.

In contrast, the Euclidean distance measures the straight-line distance between two points and considers diagonal movement as well:
$$
d = \sqrt{(x_1 - x_2)^2 + (y_1 - y_2)^2}
$$
The city-block distance is often used in algorithms that operate on grid-based structures, such as pathfinding algorithms in computer science or distance calculations in image processing.

#### Chessboard distance

The chessboard distance, also known as the Chebyshev distance or L∞ (L-infinity) distance, is a measure of the distance between two points in a grid-based system, similar to the city-block distance. However, unlike the city-block distance that allows movement only along grid lines, the chessboard distance allows movement in all directions, including diagonals.

For two points \((x_1, y_1)\) and \((x_2, y_2)\), the chessboard distance \(d\) is calculated as:

$$
 d = \max(|x_1 - x_2|, |y_1 - y_2|) 
$$
This distance is the maximum of the absolute differences in the x-coordinates and y-coordinates. It represents the length of the shortest path between two points that follows either horizontal, vertical, or diagonal movements.

Graphically, the chessboard distance corresponds to the minimum number of squares a king would need to move on a chessboard to reach the destination square from the starting square.

![image-20231218165500092](.\images\image-20231218165500092.png)

### Averaging K different noisy images

![image-20231218171024073](.\images\image-20231218171024073.png)

### Single pixel operation

![image-20231218172036158](.\images\image-20231218172036158.png)

### Neighborhood operation 

<img src=".\images\image-20231218172149802.png" alt="image-20231218172149802" style="zoom:50%;" />

### Spatial Transform

![image-20231218172718030](.\images\image-20231218172718030.png)

![image-20231218172724618](.\images\image-20231218172724618.png)

### Affine Transform

<a id="AF"></a>

![image-20231218150713208](.\images\image-20231218150713208.png)

### Nearest Neighborhood Interpolation

![image-20231218152933317](.\images\image-20231218152933317.png)

### Bilinear Interpolation

![image-20231218153140109](.\images\image-20231218153140109.png)

### Intensity Transform

In the context of digital image processing, an intensity transformation represented by the equation \(g[x, y] = T[f[x, y]]\) is a pointwise operation on pixel intensities. Here, \(f[x, y]\) represents the original pixel intensity at location \((x, y)\), \(g[x, y]\) represents the transformed pixel intensity at the same location, and \(T\) is a unary function that defines the mapping from the original intensity to the transformed intensity.

The function \(T\) is a mapping or transformation function that operates independently on each pixel in the image. It defines how the pixel intensities are changed to obtain the transformed image. The transformation function \(T\) can be chosen based on the specific requirements of image enhancement, correction, or manipulation.

Common examples of intensity transformations include:

1. **Linear Transformations:**
   $$
   g[x, y] = a \cdot f[x, y] + b
   $$
   
   where \(a\) and \(b\) are constants. This equation represents a linear mapping of pixel intensities, allowing for contrast adjustments and brightness control.
   
2. **Power-Law (Gamma) Transformations:**
   $$
   g[x, y] = c \cdot (f[x, y])^{\gamma}
   $$
   where \(c\) and \(\gamma\) are constants. This transformation is often used for adjusting the dynamic range of an image.
   
3. **Logarithmic Transformations:**
   $$
   g[x, y] = c \cdot \log(1 + f[x, y])
   $$
   where \(c\) is a constant. This transformation is useful for expanding the intensity values in the darker regions of an image.
   
4. **Piecewise Linear Transformations:**
   The mapping function \(T\) is defined differently in different regions of the input intensity range. This allows for more flexible and customized transformations.

5. **Histogram Equalization:**
   A non-linear mapping that redistributes pixel intensities to achieve a more uniform histogram, enhancing the overall contrast of the image.

6. **Thresholding:**
   A binary transformation where pixel values are set to 0 or 1 based on whether they fall below or above a certain threshold.

These intensity transformations are applied independently to each pixel in the image, providing a way to enhance or manipulate the visual characteristics of the image based on the desired outcome. The choice of the transformation function depends on the specific goals of image processing, such as enhancing contrast, reducing noise, or highlighting certain features.

### Spatial Filtering

<img src=".\images\image-20231218192814421.png" alt="image-20231218192814421" style="zoom: 50%;" />

<img src=".\images\image-20231218192924846.png" alt="image-20231218192924846" style="zoom:50%;" />

### Image Negative 

<img src=".\images\image-20231218193120657.png" alt="image-20231218193120657" style="zoom:50%;" />

### Gamma Transformations

Power-law (gamma) transformations, also known as gamma correction, are a type of intensity transformation commonly used in digital image processing. The transformation function is given by:

$$
g(x, y) = c \cdot (f(x, y))^{\gamma}
$$
where:
- \( g(x, y) \) is the transformed pixel intensity.
- \( f(x, y) \) is the original pixel intensity.
- \( c \) is a constant for scaling.
- \( \gamma \) is the gamma value, which determines the shape of the transformation curve.

Here's a breakdown of the components:

- **Gamma (\( \gamma \)):**
  - \( \gamma \) is a parameter that controls the shape of the curve. If \( \gamma < 1 \), the transformation enhances the intensities of darker pixels, while \( \gamma > 1 \) enhances the intensities of brighter pixels. \( \gamma = 1 \) results in a linear transformation.

- **Scaling Constant (\( c \)):**
  - \( c \) is a scaling factor that adjusts the overall intensity range. It is chosen to ensure that the output intensities remain in the valid range (e.g., [0, 255] for an 8-bit image).

The power-law transformation is often used for various purposes:

1. **Gamma Correction:**
   - Adjusting the gamma value can correct the non-linear response of display devices, making images appear more natural.

2. **Contrast Adjustment:**
   - Enhancing or reducing contrast by tuning the gamma parameter.

3. **Dynamic Range Compression/Expansion:**
   - Compressing or expanding the dynamic range of intensities.

4. **Image Enhancement:**
   - Highlighting details in either darker or brighter regions of an image.

<img src=".\images\image-20231218194122741.png" alt="image-20231218194122741" style="zoom:50%;" />

### Contrast stretching

<img src=".\images\image-20231218195141208.png" alt="image-20231218195141208" style="zoom:50%;" />



### Thresholding

<img src=".\images\image-20231218195123182.png" alt="image-20231218195123182" style="zoom:50%;" />

### Histogram

<img src=".\images\image-20231218201208158.png" alt="image-20231218201208158" style="zoom:50%;" />

<img src=".\images\image-20231218201332558.png" alt="image-20231218201332558" style="zoom:50%;" />

### Histogram Equalization

<img src=".\images\image-20231218201504332.png" alt="image-20231218201504332" style="zoom:50%;" />

![image-20231218202227689](.\images\image-20231218202227689.png)

### Average Blur

![image-20231218203808058](.\images\image-20231218203808058.png)

```
float r = 0;
for (int m=-M;m<=M;m++)
	for (int n=-N;n<=N;n++)
	{
		r+=f[x+m,y+n]*mask[M+m,N+n];
	}
g[x , y]=S(r);
```



<img src=".\images\image-20231218204121940.png" alt="image-20231218204121940" style="zoom:50%;" />

<img src=".\images\image-20231218203440521.png" alt="image-20231218203440521" style="zoom: 50%;" />

### Gaussian Blur

<img src=".\images\image-20231218205205276.png" alt="image-20231218205205276" style="zoom:50%;" />

​								**M=N=(int)3σ**

<img src=".\images\image-20231218205300939.png" alt="image-20231218205300939" style="zoom: 40%;" /><img src=".\images\image-20231218205659985.png" alt="image-20231218205659985" style="zoom: 40%;" />

### Median Filter

<img src=".\images\image-20231218210218407.png" alt="image-20231218210218407" style="zoom:50%;" />

<img src=".\images\image-20231218210320552.png" alt="image-20231218210320552" style="zoom:50%;" />

<img src=".\images\image-20231218210501096.png" alt="image-20231218210501096" style="zoom:50%;" />

### Laplacian

<img src=".\images\image-20231218211137359.png" alt="image-20231218211137359" style="zoom:50%;" />

<img src=".\images\image-20231218211215475.png" alt="image-20231218211215475" style="zoom:50%;" />

<img src=".\images\image-20231218211228696.png" alt="image-20231218211228696" style="zoom:50%;" />

<img src=".\images\image-20231218211238312.png" alt="image-20231218211238312" style="zoom:50%;" />

<img src=".\images\image-20231218211242798.png" alt="image-20231218211242798" style="zoom:60%;" />

​                                  **coefficient:          1              1              1               1            -4**

<img src=".\images\image-20231218211355409.png" alt="image-20231218211355409" style="zoom: 50%;" />

<img src=".\images\image-20231218211557948.png" alt="image-20231218211557948" style="zoom:50%;" />

### Sharpening Filter

<img src=".\images\image-20231218211939611.png" alt="image-20231218211939611" style="zoom:50%;" />

<img src=".\images\image-20231218212051906.png" alt="image-20231218212051906" style="zoom:50%;" />

### Unsharp Masking

<img src=".\images\image-20231218213214790.png" alt="image-20231218213214790" style="zoom:50%;" />

<img src=".\images\image-20231218213251025.png" alt="image-20231218213251025" style="zoom:50%;" />

<img src=".\images\image-20231218213259499.png" alt="image-20231218213259499" style="zoom:33%;" />

### Magnitude of Gradient

<img src=".\images\image-20231218213555139.png" alt="image-20231218213555139" style="zoom:50%;" />

Approximate of magnitude (suitable computationally)

<img src=".\images\image-20231218213636145.png" alt="image-20231218213636145" style="zoom:50%;" />

### Direction of Gradient

<img src=".\images\image-20231218221248182.png" alt="image-20231218221248182" style="zoom:50%;" />

<img src=".\images\image-20231218221529578.png" alt="image-20231218221529578" style="zoom:50%;" />

<img src=".\images\image-20231218221855078.png" alt="image-20231218221855078" style="zoom:50%;" />

### Sobel Mask

<img src=".\images\image-20231218222058532.png" alt="image-20231218222058532" style="zoom:50%;" />

<img src=".\images\image-20231218222752345.png" alt="image-20231218222752345" style="zoom:50%;" />

### Combining Spatial Enhancement Methods

<img src=".\images\image-20231218223001935.png" alt="image-20231218223001935" style="zoom:50%;" />

![image-20231218223041924](.\images\image-20231218223041924.png)

### FFT Shift

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219150129589.png" alt="image-20231219150129589" style="zoom:40%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219154725484.png" alt="image-20231219154725484" style="zoom:50%;" />

### Separability

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219150158338.png" alt="image-20231219150158338" style="zoom: 67%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219150256784.png" alt="image-20231219150256784" style="zoom:67%;" />

### Filtering in the Frequency Domain

![image-20231219150802002](C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219150802002.png)

### Low pass/High pass

![image-20231219152030413](C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219152030413.png)

### Homomorphic Filtering

![image-20231219155043561](C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219155043561.png)

### Band reject

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219160847908.png" alt="image-20231219160847908" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219161008286.png" alt="image-20231219161008286" style="zoom:50%;" />

### Notch Reject

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219165431790.png" alt="image-20231219165431790" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219165502422.png" alt="image-20231219165502422" style="zoom: 50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219165548187.png" alt="image-20231219165548187" style="zoom:50%;" />

### Inverse Filtering

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219170714487.png" alt="image-20231219170714487" style="zoom:50%;" />

### HSI Model

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219201634119.png" alt="image-20231219201634119" style="zoom:50%;" />

### HSV Model



<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219203444530.png" alt="image-20231219203444530" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219203943144.png" alt="image-20231219203943144" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219203209639.png" alt="image-20231219203209639" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219203456266.png" alt="image-20231219203456266" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219203129385.png" alt="image-20231219203129385" style="zoom:50%;" />

### Full Color Image Processing (HIS/HSV) 

```C++
#include <opencv2/opencv.hpp>

int main() {
    // Read an RGB image
    cv::Mat rgbImage = cv::imread("path_to_rgb_image.jpg");

    if (rgbImage.empty()) {
        std::cerr << "Error: Could not read the image." << std::endl;
        return -1;
    }

    // Convert RGB to HSV
    cv::Mat hsvImage;
    cv::cvtColor(rgbImage, hsvImage, cv::COLOR_BGR2HSV);

    // Process each component (Hue, Saturation, Value) as needed
    // Example: Increase the saturation
    for (int y = 0; y < hsvImage.rows; ++y) {
        for (int x = 0; x < hsvImage.cols; ++x) {
            // Access and modify the pixel values directly
            hsvImage.at<cv::Vec3b>(y, x)[1] = cv::saturate_cast<uchar>(hsvImage.at<cv::Vec3b>(y, x)[1] * 1.5);
        }
    }

    // Convert HSV back to RGB
    cv::Mat processedImage;
    cv::cvtColor(hsvImage, processedImage, cv::COLOR_HSV2BGR);

    // Display the original and processed images
    cv::imshow("Original RGB Image", rgbImage);
    cv::imshow("Processed Image (Increased Saturation)", processedImage);
    cv::waitKey(0);

    return 0;
}

```

### Color Matrix

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219212621309.png" alt="image-20231219212621309" style="zoom:50%;" />

### Erosion

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220103956193.png" alt="image-20231220103956193" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220104508966.png" alt="image-20231220104508966" style="zoom:50%;" />

![image-20231220104525898](C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220104525898.png)

### Dilation

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220104015991.png" alt="image-20231220104015991" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220104541829.png" alt="image-20231220104541829" style="zoom:50%;" />

### Open and close 

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220104944434.png" alt="image-20231220104944434" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220104846830.png" alt="image-20231220104846830" style="zoom:50%;" />

### Detection of Isolated Point

![image-20231220105722686](C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220105722686.png)

### Line Detection

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220110019082.png" alt="image-20231220110019082" style="zoom:50%;" />

### Image gradient

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220111333699.png" alt="image-20231220111333699" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220111342394.png" alt="image-20231220111342394" style="zoom: 50%;" />

### Gradient operators

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220111417774.png" alt="image-20231220111417774" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220111506212.png" alt="image-20231220111506212" style="zoom:50%;" />

### Marr-Hildreth edge detector

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220152128883.png" alt="image-20231220152128883" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220151600666.png" alt="image-20231220151600666" style="zoom: 67%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220151200607.png" alt="image-20231220151200607" style="zoom:50%;" />

### Canny edge detector

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220152325435.png" alt="image-20231220152325435" style="zoom:50%;" />

https://zhuanlan.zhihu.com/p/42122107

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220153712441.png" alt="image-20231220153712441" style="zoom:50%;" />

### Intensity   thresholding

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220154140433.png" alt="image-20231220154140433" style="zoom:50%;" />

### Basic Global Thresholding

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220154328229.png" alt="image-20231220154328229" style="zoom:50%;" />

### Connected-component labeling

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220154513583.png" alt="image-20231220154513583" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220154537238.png" alt="image-20231220154537238" style="zoom:50%;" />

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220154607871.png" alt="image-20231220154607871" style="zoom:50%;" />

### Hough Transform

https://blog.csdn.net/YuYunTan/article/details/80141392

![image-20231220165725327](C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220165725327.png)

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231220165518149.png" alt="image-20231220165518149"  />

## Code

### Digital Image

```c++
#include <opencv2/opencv.hpp>
#include <iostream>

int main() {
    // Load image
    cv::Mat image = cv::imread("path_to_your_image.jpg");

    // Check if the image was loaded successfully
    if (image.empty()) {
        std::cerr << "Error: Could not load the image." << std::endl;
        return -1;
    }

    // Show original image
    cv::imshow("Original Image", image);
    cv::waitKey(0);

    // Read pixel value at (100, 100)
    uchar v = image.at<uchar>(100, 100);
    std::cout << "Pixel value at (100, 100): " << static_cast<int>(v) << std::endl;

    // Write pixel values at (100, 100), (101, 100), (100, 101), (101, 101)
    image.at<uchar>(100, 100) = 255;
    image.at<uchar>(101, 100) = 255;
    image.at<uchar>(100, 101) = 255;
    image.at<uchar>(101, 101) = 255;

    // Show modified image
    cv::imshow("Modified Image", image);
    cv::waitKey(0);

    return 0;
}
```

### Image Resolution

```c++
#include <opencv2/opencv.hpp>
#include <iostream>

int main() {
    // Load an image
    cv::Mat image = cv::imread("path_to_your_image.jpg");

    // Check if the image was loaded successfully
    if (image.empty()) {
        std::cerr << "Error: Could not load the image." << std::endl;
        return -1;
    }

    // Get image resolution (width and height)
    int width = image.cols;
    int height = image.rows;

    // Print the resolution
    std::cout << "Image Resolution: Width = " << width << ", Height = " << height << std::endl;

    return 0;
}
```

### Inverse Mapping

```c++
#include <opencv2/opencv.hpp>

cv::Mat IM(const cv::Mat& f) {
    int w = f.cols;
    int h = f.rows;

    int ow = w / 2;
    int oh = h / 2;

    cv::Mat g(oh, ow, f.type());

    for (int y = 0; y < oh; y++) {
        for (int x = 0; x < ow; x++) {
            int u = x * 2;
            int v = y * 2;

            g.at<uchar>(y, x) = f.at<uchar>(v, u);
        }
    }

    return g;
}

int main() {
    // Load an image
    cv::Mat image = cv::imread("path_to_your_image.jpg", cv::IMREAD_GRAYSCALE);

    // Check if the image was loaded successfully
    if (image.empty()) {
        std::cerr << "Error: Could not load the image." << std::endl;
        return -1;
    }

    // Apply down-sampling
    cv::Mat result = IM(image);

    // Display the original and down-sampled images
    cv::imshow("Original Image", image);
    cv::imshow("Down-sampled Image", result);
    cv::waitKey(0);

    return 0;
}
```

### Affine Transform

<img src=".\images\image-20231218150117077.png" alt="image-20231218150117077" style="zoom:40%;" />

```c++
#include <opencv2/opencv.hpp>
struct Matrix {
    double m11, m12, m21, m22, m31, m32;
};

cv::Mat ST(const cv::Mat& f, const Matrix& M) {
    int w = f.cols;
    int h = f.rows;

    cv::Mat g(h, w, f.type());

    for (int y = 0; y < h; y++)
        for (int x = 0; x < w; x++) {
            int u = static_cast<int>(M.m11 * x + M.m21 * y + M.m31);
            int v = static_cast<int>(M.m12 * x + M.m22 * y + M.m32);

            if (u >= 0 && u < w && v >= 0 && v < h)
                g.at<uchar>(y, x) = f.at<uchar>(v, u);
        }

    return g;
}

Matrix createI() {
    Matrix m;
    m.m11 = 1;
    m.m12 = 0;
    m.m21 = 0;
    m.m22 = 1;
    m.m31 = 0;
    m.m32 = 0;
    return m;
}

Matrix flipV(int h) {
    Matrix m;
    m.m11 = 1;
    m.m12 = 0;
    m.m21 = 0;
    m.m22 = -1;
    m.m31 = 0;
    m.m32 = h - 1;
    return m;
}

Matrix flipH(int w) {
    Matrix m;
    m.m11 = -1;
    m.m12 = 0;
    m.m21 = 0;
    m.m22 = 1;
    m.m31 = w - 1;
    m.m32 = 0;
    return m;
}

Matrix translate(int dx, int dy) {
    Matrix m;
    m.m11 = 1;
    m.m12 = 0;
    m.m21 = 0;
    m.m22 = 1;
    m.m31 = -dx;
    m.m32 = -dy;
    return m;
}

Matrix scale(float k) {
    Matrix m;
    m.m11 = 1 / k;
    m.m12 = 0;
    m.m21 = 0;
    m.m22 = 1 / k;
    m.m31 = 0;
    m.m32 = 0;
    return m;
}

int main() {
    // Load an image
    cv::Mat image = cv::imread("path_to_your_image.jpg", cv::IMREAD_GRAYSCALE);

    // Check if the image was loaded successfully
    if (image.empty()) {
        std::cerr << "Error: Could not load the image." << std::endl;
        return -1;
    }

    // Show the original image
    cv::imshow("Original Image", image);
    cv::waitKey(0);

    // Apply transformations
    // cv::Mat result = ST(image, createI());
    // cv::Mat result = ST(image, flipV(image.rows));
    // cv::Mat result = ST(image, flipH(image.cols));
    // cv::Mat result = ST(image, translate(150, 100));
    // cv::Mat result = ST(image, scale(0.5f));
    cv::Mat result = ST(image, scale(2));

    // Show the transformed image
    cv::imshow("Transformed Image", result);
    cv::waitKey(0);

    return 0;
}
```

### Composted Affine Transform

```c++
#include <opencv2/opencv.hpp>
#include <cmath>

cv::Mat ZoomAt(const cv::Mat& f, float x0, float y0, float k) {
    int w = f.cols;
    int h = f.rows;

    cv::Mat g(h, w, f.type());

    for (int y = 0; y < h; y++)
        for (int x = 0; x < w; x++) {
            int u = static_cast<int>((x - x0) / k + x0);
            int v = static_cast<int>((y - y0) / k + y0);

            if (u >= 0 && u < w && v >= 0 && v < h)
                g.at<uchar>(y, x) = f.at<uchar>(v, u);
        }

    return g;
}

cv::Mat localZooming(const cv::Mat& f, float x0, float y0, float k, float R) {
    int w = f.cols;
    int h = f.rows;

    cv::Mat g(h, w, f.type());

    for (int y = 0; y < h; y++)
        for (int x = 0; x < w; x++) {
            double distance = std::sqrt((x - x0) * (x - x0) + (y - y0) * (y - y0));

            if (distance < R) {
                double t = distance / R;

                double s = k * (1 - t) + t;

                int u = static_cast<int>((x - x0) / s + x0);
                int v = static_cast<int>((y - y0) / s + y0);

                if (u >= 0 && u < w && v >= 0 && v < h)
                    g.at<uchar>(y, x) = f.at<uchar>(v, u);
            } else {
                g.at<uchar>(y, x) = f.at<uchar>(y, x);
            }
        }

    return g;
}

int main() {
    // Load an image
    cv::Mat image = cv::imread("path_to_your_image.jpg", cv::IMREAD_GRAYSCALE);

    // Check if the image was loaded successfully
    if (image.empty()) {
        std::cerr << "Error: Could not load the image." << std::endl;
        return -1;
    }

    // Show the original image
    cv::imshow("Original Image", image);
    cv::waitKey(0);

    // Example usage of the ZoomAt function
    cv::Mat result1 = ZoomAt(image, 256, 256, 5);

    // Example usage of the localZooming function
    // cv::Mat result2 = localZooming(image, 266, 266, 0.5f, 50);
    // cv::Mat result3 = localZooming(image, 266, 266, 2, 50);

    // Show the results
    cv::imshow("ZoomAt Result", result1);
    // cv::imshow("LocalZooming Result (k=0.5)", result2);
    // cv::imshow("LocalZooming Result (k=2)", result3);
    
    cv::waitKey(0);

    return 0;
}

```

### Gamma Transformations-code

Here's an example of how to implement a gamma transformation in C++ using OpenCV:

```cpp
#include <opencv2/opencv.hpp>

int main() {
    // Read an image from file
    cv::Mat image = cv::imread("path_to_image.jpg", cv::IMREAD_GRAYSCALE);

    if (image.empty()) {
        std::cerr << "Error: Could not read the image." << std::endl;
        return -1;
    }

    // Define gamma value
    double gamma = 1.5;

    // Apply gamma transformation
    cv::Mat gammaCorrected;
    cv::pow(image / 255.0, gamma, gammaCorrected);

    // Convert back to 8-bit scale
    gammaCorrected = gammaCorrected * 255;

    // Display the original and gamma-corrected images
    cv::imshow("Original Image", image);
    cv::imshow("Gamma Corrected Image", gammaCorrected);
    cv::waitKey(0);

    return 0;
}
```

Make sure to replace "path_to_image.jpg" with the actual path to your image file. Experimenting with different gamma values allows you to observe the impact of the power-law transformation on the image.

### Bit-plane slicing 

```c++
import cv2
import numpy as np

# Read an image
image = cv2.imread('path_to_image.jpg', cv2.IMREAD_GRAYSCALE)

# Perform bit-plane slicing
bit_planes = [np.bitwise_and(image, 2**i) for i in range(8)]

# Display the original and bit-plane sliced images
cv2.imshow('Original Image', image)
for i, plane in enumerate(bit_planes):
    cv2.imshow(f'Bit Plane {i}', plane * 255)

cv2.waitKey(0)
cv2.destroyAllWindows()

```

### Brightness Transformation

```c++
#include <opencv2/opencv.hpp>
#include <matplotlibcpp.h>

namespace plt = matplotlibcpp;

int main() {
    // Read an image
    cv::Mat image = cv::imread("path_to_image.jpg", cv::IMREAD_GRAYSCALE);

    if (image.empty()) {
        std::cerr << "Error: Could not read the image." << std::endl;
        return -1;
    }

    // Basic intensity transformations
    int c = 50;  // constant for addition
    float k = 1.5;  // constant for multiplication
    cv::Mat g_addition, g_multiplication;

    // g[x, y] = f[x, y] + c
    cv::add(image, c, g_addition);

    // g[x, y] = k * f[x, y]
    cv::multiply(image, k, g_multiplication);

    // Saturation Operation (clipping pixel values to [0, 255])
    cv::Mat g_saturated_addition = cv::min(cv::max(image + c, 0), 255);
    cv::Mat g_saturated_multiplication = cv::min(cv::max(image * k, 0), 255);

    // Plot the function curves
    plt::subplot(2, 2, 1);
    plt::plot(image.row(100));  // Plot a row for visualization
    plt::title("Original Image");

    plt::subplot(2, 2, 2);
    plt::plot(g_addition.row(100));
    plt::title("g[x, y] = f[x, y] + c");

    plt::subplot(2, 2, 3);
    plt::plot(g_multiplication.row(100));
    plt::title("g[x, y] = k * f[x, y]");

    plt::subplot(2, 2, 4);
    plt::plot(g_saturated_addition.row(100));
    plt::title("S(g[x, y] + c)");

    plt::show();

    return 0;
}

```

### Average Blur-code

```c++
#include <opencv2/opencv.hpp>

// Function to apply an average filter to an image
cv::Mat averageFilter(const cv::Mat& inputImage, int kernelSize) {
    // Create an output image with the same size and type as the input image
    cv::Mat outputImage = inputImage.clone();

    // Define the kernel (square matrix) for the average filter
    cv::Mat kernel = cv::Mat::ones(kernelSize, kernelSize, CV_32F) / (float)(kernelSize * kernelSize);

    // Apply the filter to the image
    cv::filter2D(inputImage, outputImage, -1, kernel, cv::Point(-1, -1), 0, cv::BORDER_DEFAULT);

    return outputImage;
}

int main() {
    // Read an image
    cv::Mat inputImage = cv::imread("path_to_image.jpg", cv::IMREAD_COLOR);

    if (inputImage.empty()) {
        std::cerr << "Error: Could not read the image." << std::endl;
        return -1;
    }

    // Convert the image to grayscale
    cv::cvtColor(inputImage, inputImage, cv::COLOR_BGR2GRAY);

    // Apply the average filter with a kernel size of 3x3
    int kernelSize = 3;
    cv::Mat outputImage = averageFilter(inputImage, kernelSize);

    // Display the original and filtered images
    cv::imshow("Original Image", inputImage);
    cv::imshow("Average Filtered Image", outputImage);
    cv::waitKey(0);

    return 0;
}

```

### Unsharp Masking-code

```C++
#include <opencv2/opencv.hpp>

int main() {
    // Read an image
    cv::Mat inputImage = cv::imread("path_to_image.jpg", cv::IMREAD_COLOR);

    if (inputImage.empty()) {
        std::cerr << "Error: Could not read the image." << std::endl;
        return -1;
    }

    // Convert the image to grayscale
    cv::Mat grayImage;
    cv::cvtColor(inputImage, grayImage, cv::COLOR_BGR2GRAY);

    // Apply Gaussian blur to the grayscale image
    cv::Mat blurredImage;
    cv::GaussianBlur(grayImage, blurredImage, cv::Size(5, 5), 1.5);

    // Calculate the unsharp mask
    cv::Mat unsharpMask = grayImage - blurredImage;

    // Add the unsharp mask back to the original image
    cv::Mat sharpenedImage = grayImage + unsharpMask;

    // Display the original and sharpened images
    cv::imshow("Original Image", grayImage);
    cv::imshow("Sharpened Image", sharpenedImage);
    cv::waitKey(0);

    return 0;
}

```

### Low pass/High pass-code

![image-20231219151213735](C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219151213735.png)

![image-20231219152619171](C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219152619171.png)

```c++
#include <opencv2/opencv.hpp>

void createLowPassFilter(cv::Mat& filter, int rows, int cols, int cutoff) {
    filter = cv::Mat(rows, cols, CV_32F);

    for (int u = 0; u < rows; ++u) {
        for (int v = 0; v < cols; ++v) {
            float distance = sqrt(pow(u - rows / 2, 2) + pow(v - cols / 2, 2));
            filter.at<float>(u, v) = (distance <= cutoff) ? 1.0 : 0.0;
        }
    }
}

int main() {
    // Read an image
    cv::Mat image = cv::imread("path_to_image.jpg", cv::IMREAD_GRAYSCALE);

    if (image.empty()) {
        std::cerr << "Error: Could not read the image." << std::endl;
        return -1;
    }

    // Perform DFT
    cv::Mat complexImage;
    cv::dft(image, complexImage, cv::DFT_COMPLEX_OUTPUT);

    // Create a low-pass filter
    int rows = image.rows;
    int cols = image.cols;
    int cutoffFrequency = 30;  // Adjust as needed
    cv::Mat lowPassFilter;
    createLowPassFilter(lowPassFilter, rows, cols, cutoffFrequency);

    // Apply the filter to the frequency domain representation
    cv::Mat filteredImage;
    cv::multiply(complexImage, lowPassFilter, filteredImage);

    // Perform Inverse DFT to get the filtered image back to the spatial domain
    cv::Mat resultImage;
    cv::idft(filteredImage, resultImage, cv::DFT_REAL_OUTPUT | cv::DFT_SCALE);

    // Display the original and filtered images
    cv::imshow("Original Image", image);
    cv::imshow("Filtered Image", resultImage);
    cv::waitKey(0);

    return 0;
}

```

### Band reject-code

To implement a band reject (or band-stop) filter in C++, you can use the Discrete Fourier Transform (DFT) provided by libraries like OpenCV. The band reject filter is designed to attenuate or eliminate a specific range of frequencies while allowing other frequencies to pass.

Here's an example using OpenCV to create a band reject filter:

```cpp
#include <opencv2/opencv.hpp>

void createBandRejectFilter(cv::Mat& filter, int rows, int cols, int lowerCutoff, int upperCutoff) {
    filter = cv::Mat(rows, cols, CV_32F);

    for (int u = 0; u < rows; ++u) {
        for (int v = 0; v < cols; ++v) {
            float distance = sqrt(pow(u - rows / 2, 2) + pow(v - cols / 2, 2));
            filter.at<float>(u, v) = (distance >= lowerCutoff && distance <= upperCutoff) ? 0.0 : 1.0;
        }
    }
}

int main() {
    // Read an image
    cv::Mat image = cv::imread("path_to_image.jpg", cv::IMREAD_GRAYSCALE);

    if (image.empty()) {
        std::cerr << "Error: Could not read the image." << std::endl;
        return -1;
    }

    // Perform DFT
    cv::Mat complexImage;
    cv::dft(image, complexImage, cv::DFT_COMPLEX_OUTPUT);

    // Create a band reject filter
    int rows = image.rows;
    int cols = image.cols;
    int lowerCutoffFrequency = 10;  // Adjust as needed
    int upperCutoffFrequency = 50; // Adjust as needed
    cv::Mat bandRejectFilter;
    createBandRejectFilter(bandRejectFilter, rows, cols, lowerCutoffFrequency, upperCutoffFrequency);

    // Apply the filter to the frequency domain representation
    cv::Mat filteredImage;
    cv::multiply(complexImage, bandRejectFilter, filteredImage);

    // Perform Inverse DFT to get the filtered image back to the spatial domain
    cv::Mat resultImage;
    cv::idft(filteredImage, resultImage, cv::DFT_REAL_OUTPUT | cv::DFT_SCALE);

    // Display the original and filtered images
    cv::imshow("Original Image", image);
    cv::imshow("Filtered Image", resultImage);
    cv::waitKey(0);

    return 0;
}
```

This example creates a band reject filter that attenuates or eliminates frequencies within a specified range (between `lowerCutoffFrequency` and `upperCutoffFrequency`). Adjust these parameters based on the frequency range you want to reject.

As with other frequency domain filtering techniques, this example assumes a grayscale image. Modifications may be needed for color images. Additionally, more sophisticated filter designs and techniques exist, depending on specific requirements and the characteristics of the signal or image you are processing.

### RGB Model

In OpenCV, you can access and manipulate individual color channels of an image using the `cv::split` and `cv::merge` functions. Each channel is represented as a separate matrix. For a color image in the BGR format (Blue, Green, Red), the first channel corresponds to blue, the second to green, and the third to red.

Here's an example of how to extract and work with the red channel of an RGB image:

```cpp
#include <opencv2/opencv.hpp>

int main() {
    // Read an RGB image from file
    cv::Mat rgbImage = cv::imread("path_to_image.jpg");

    // Check if the image was successfully loaded
    if (rgbImage.empty()) {
        std::cerr << "Error: Could not read the image." << std::endl;
        return -1;
    }

    // Split the RGB image into individual channels
    std::vector<cv::Mat> channels;
    cv::split(rgbImage, channels);

    // Access the red channel (third channel)
    cv::Mat redChannel = channels[2];

    // Display the original image and the red channel
    cv::imshow("Original Image", rgbImage);
    cv::imshow("Red Channel", redChannel);
    cv::waitKey(0);

    return 0;
}
```

In this example:

1. The `cv::split` function is used to split the RGB image into individual channels, and the result is stored in the `channels` vector.

2. The red channel (third channel) is accessed using `channels[2]`. Note that array indices are 0-based in C++, so the blue channel is `channels[0]`, green is `channels[1]`, and red is `channels[2]`.

3. The red channel is displayed using `cv::imshow`.

Remember to replace `"path_to_image.jpg"` with the actual path to your image file. Adjust the code accordingly if your image is in a different color format or if you're using a different library or framework.

### Pseudo color Image Processing

Intensity slicing is a technique in image processing where certain ranges of intensity values in an image are highlighted or emphasized by assigning specific colors to those intensity ranges. Pseudocoloring involves mapping intensity values to color to enhance visual representation. Here's a basic outline of intensity slicing with pseudocoloring in image processing:

1. **Load the Image:**
   - Read an image from a file or acquire it through other means.

2. **Convert to Grayscale:**
   - If the image is not already in grayscale, convert it. You can use the average of the RGB channels or other methods.

3. **Intensity Slicing:**
   - Define intensity ranges or thresholds that you want to emphasize in the image.
   - Assign specific colors to those intensity ranges.

4. **Pseudocoloring:**
   - Map the intensity values to colors based on the defined intensity ranges.
   - Create a new color image where each intensity value is represented by a corresponding color.

5. **Display the Result:**
   - Show the original grayscale image and the pseudocolored result for comparison.

Here's a simple example in C++ using OpenCV for intensity slicing and pseudocoloring:

```cpp
#include <opencv2/opencv.hpp>

int main() {
    // Read a grayscale image
    cv::Mat grayscaleImage = cv::imread("path_to_grayscale_image.jpg", cv::IMREAD_GRAYSCALE);

    if (grayscaleImage.empty()) {
        std::cerr << "Error: Could not read the image." << std::endl;
        return -1;
    }

    // Define intensity thresholds (adjust as needed)
    int lowThreshold = 100;
    int highThreshold = 200;

    // Create a pseudocolored image
    cv::Mat pseudocoloredImage = cv::Mat::zeros(grayscaleImage.size(), CV_8UC3);

    // Apply intensity slicing and pseudocoloring
    for (int y = 0; y < grayscaleImage.rows; ++y) {
        for (int x = 0; x < grayscaleImage.cols; ++x) {
            uchar intensity = grayscaleImage.at<uchar>(y, x);

            if (intensity < lowThreshold) {
                pseudocoloredImage.at<cv::Vec3b>(y, x) = cv::Vec3b(0, 0, 255);  // Red
            } else if (intensity >= lowThreshold && intensity < highThreshold) {
                pseudocoloredImage.at<cv::Vec3b>(y, x) = cv::Vec3b(0, 255, 0);  // Green
            } else {
                pseudocoloredImage.at<cv::Vec3b>(y, x) = cv::Vec3b(255, 0, 0);  // Blue
            }
        }
    }

    // Display the original grayscale image and the pseudocolored result
    cv::imshow("Grayscale Image", grayscaleImage);
    cv::imshow("Pseudocolored Image", pseudocoloredImage);
    cv::waitKey(0);

    return 0;
}
```

In this example:
- The intensity values below `lowThreshold` are assigned the color red.
- Intensity values between `lowThreshold` and `highThreshold` are assigned the color green.
- Intensity values above `highThreshold` are assigned the color blue.

Adjust the thresholds and colors according to your specific requirements.

### Full Color Image Processing

<img src="C:\Users\admin\Desktop\DIP-typora\Outline of Digital Image Processing (2023V2)\images\image-20231219211116968.png" alt="image-20231219211116968" style="zoom:50%;" />

```C++
#include <opencv2/opencv.hpp>

int main() {
    // Read an RGB image
    cv::Mat rgbImage = cv::imread("path_to_rgb_image.jpg");

    if (rgbImage.empty()) {
        std::cerr << "Error: Could not read the image." << std::endl;
        return -1;
    }

    // Split the RGB image into individual channels
    std::vector<cv::Mat> channels;
    cv::split(rgbImage, channels);

    // Process each channel separately (Example: apply Gaussian blur)
    for (int i = 0; i < 3; ++i) {
        cv::GaussianBlur(channels[i], channels[i], cv::Size(5, 5), 0);
    }

    // Merge the processed channels back into an RGB image
    cv::Mat processedImage;
    cv::merge(channels, processedImage);

    // Display the original and processed images
    cv::imshow("Original RGB Image", rgbImage);
    cv::imshow("Processed RGB Image", processedImage);
    cv::waitKey(0);

    return 0;
}

```

### Color Matrix-code

**1123-color-matrix.txt**

```C++
#include <opencv2/opencv.hpp>

using namespace cv;

struct ARGB {
    uchar A;
    uchar R;
    uchar G;
    uchar B;
};

ARGB S(double v) {
    ARGB result;
    result.A = 255;
    if (v > 255) {
        result.R = result.G = result.B = 255;
    } else if (v < 0) {
        result.R = result.G = result.B = 0;
    } else {
        result.R = result.G = result.B = static_cast<uchar>(v);
    }
    return result;
}

Mat matrix_transform(Mat& input, Mat& transformation) {
    int w = input.cols;
    int h = input.rows;

    Mat output = Mat::zeros(h, w, input.type());

    for (int y = 0; y < h; y++) {
        for (int x = 0; x < w; x++) {
            Vec3b pixel = input.at<Vec3b>(y, x);

            float r = pixel[2];
            float g = pixel[1];
            float b = pixel[0];

            float resultR = transformation.at<float>(0, 0) * r + transformation.at<float>(1, 0) * g +
                            transformation.at<float>(2, 0) * b + transformation.at<float>(3, 0);
            float resultG = transformation.at<float>(0, 1) * r + transformation.at<float>(1, 1) * g +
                            transformation.at<float>(2, 1) * b + transformation.at<float>(3, 1);
            float resultB = transformation.at<float>(0, 2) * r + transformation.at<float>(1, 2) * g +
                            transformation.at<float>(2, 2) * b + transformation.at<float>(3, 2);

            ARGB result = S(resultR);
            output.at<Vec3b>(y, x)[2] = result.R;
            result = S(resultG);
            output.at<Vec3b>(y, x)[1] = result.G;
            result = S(resultB);
            output.at<Vec3b>(y, x)[0] = result.B;
        }
    }

    return output;
}

Mat mk_I() {
    Mat m = Mat::eye(4, 4, CV_32F);
    return m;
}

Mat RGB_BGR() {
    Mat m = Mat::zeros(4, 4, CV_32F);
    m.at<float>(0, 2) = 1;
    m.at<float>(1, 1) = 1;
    m.at<float>(2, 0) = 1;
    m.at<float>(3, 3) = 1;
    return m;
}

Mat ToGray() {
    Mat m = Mat::zeros(4, 4, CV_32F);
    float v = 1.0f / 3;
    m.at<float>(0, 0) = v;
    m.at<float>(1, 0) = v;
    m.at<float>(2, 0) = v;
    m.at<float>(0, 1) = v;
    m.at<float>(1, 1) = v;
    m.at<float>(2, 1) = v;
    m.at<float>(0, 2) = v;
    m.at<float>(1, 2) = v;
    m.at<float>(2, 2) = v;
    m.at<float>(3, 3) = 1;
    return m;
}

Mat adjustBright(float k) {
    Mat m = Mat::eye(4, 4, CV_32F);
    m.at<float>(0, 0) = k;
    m.at<float>(1, 1) = k;
    m.at<float>(2, 2) = k;
    return m;
}

Mat adjustBright2(float c) {
    Mat m = Mat::eye(4, 4, CV_32F);
    m.at<float>(3, 0) = c;
    m.at<float>(3, 1) = c;
    m.at<float>(3, 2) = c;
    return m;
}

Mat adjustS(float u) {
    Mat m = Mat::zeros(4, 4, CV_32F);
    float v1 = (1 - u) / 3 + u;
    float v2 = (1 - u) / 3;

    m.at<float>(0, 0) = v1;
    m.at<float>(1, 0) = v2;
    m.at<float>(2, 0) = v2;
    m.at<float>(0, 1) = v2;
    m.at<float>(1, 1) = v1;
    m.at<float>(2, 1) = v2;
    m.at<float>(0, 2) = v2;
    m.at<float>(1, 2) = v2;
    m.at<float>(2, 2) = v1;
    m.at<float>(3, 3) = 1;

    return m;
}

Mat CB_R(float c) {
    Mat m = Mat::eye(4, 4, CV_32F);
    m.at<float>(3, 0) = c;
    m.at<float>(3, 1) = -c / 2;
    m.at<float>(3, 2) = -c / 2;
    return m;
}

Mat CB_B(float c) {
    Mat m = Mat::eye(4, 4, CV_32F);
    m.at<float>(3, 0) = -c / c;
    m.at<float>(3, 1) = -c / 2;
    m.at<float>(3, 2) = c;
    return m;
}

Mat RGB_BRG() {
    Mat m = Mat::zeros(4, 4, CV_32F);
    m.at<float>(0, 1) = 1;
    m.at<float>(1, 2) = 1;
    m.at<float>(2, 0) = 1;
    m.at<float>(3, 3) = 1;
    return m;
}

int main() {
    Mat f = imread("path_to_image.jpg");

    if (f.empty()) {
        std::cerr << "Error: Could not read the image." << std::endl;
        return -1;
    }

    imshow("Original Image", f);

    // Example usage of transformations
    // Mat g = matrix_transform(f, mk_I());
    // Mat g = matrix_transform(f, RGB_BGR());
    // Mat g = matrix_transform(f, adjustBright(1.5f));
    // Mat g = matrix_transform(f, adjustS(0.5f));
    // Mat g = matrix_transform(f, CB_R(60));
    // Mat g = matrix_transform(f, CB_B(60));
    // Mat g = matrix_transform(f, RGB_BRG());

    // Show the result
    imshow("Transformed Image", g);
    waitKey(0);


```

### Erosion & Dilation

Certainly! Here's the C++ version of the provided erosion, dilation, open, and close functions using OpenCV:

```cpp
#include <opencv2/opencv.hpp>

cv::Mat erosion(const cv::Mat& f) {
    cv::Mat g = cv::Mat::zeros(f.size(), CV_8U);

    for (int y = 1; y < f.rows - 1; y++)
        for (int x = 1; x < f.cols - 1; x++)
            if (f.at<uchar>(y, x) == 255 && f.at<uchar>(y - 1, x) == 255 && f.at<uchar>(y + 1, x) == 255 &&
                f.at<uchar>(y, x - 1) == 255 && f.at<uchar>(y, x + 1) == 255)
                g.at<uchar>(y, x) = 255;

    return g;
}

cv::Mat dilation(const cv::Mat& f) {
    cv::Mat g = cv::Mat::zeros(f.size(), CV_8U);

    for (int y = 1; y < f.rows - 1; y++)
        for (int x = 1; x < f.cols - 1; x++)
            if (f.at<uchar>(y, x) == 255 || f.at<uchar>(y - 1, x) == 255 || f.at<uchar>(y + 1, x) == 255 ||
                f.at<uchar>(y, x - 1) == 255 || f.at<uchar>(y, x + 1) == 255)
                g.at<uchar>(y, x) = 255;

    return g;
}

cv::Mat open(const cv::Mat& f) {
    return dilation(erosion(f));
}

cv::Mat close(const cv::Mat& f) {
    return erosion(dilation(f));
}

int main() {
    cv::Mat f = cv::imread("input_image.jpg", cv::IMREAD_GRAYSCALE);

    if (f.empty()) {
        std::cerr << "Error: Could not read the image." << std::endl;
        return -1;
    }

    cv::imshow("f", f);

    cv::Mat resultErosion = erosion(f);
    cv::imshow("Erosion", resultErosion);

    cv::Mat resultDilation = dilation(f);
    cv::imshow("Dilation", resultDilation);

    cv::Mat resultOpen = open(f);
    cv::imshow("Open", resultOpen);

    cv::Mat resultClose = close(f);
    cv::imshow("Close", resultClose);

    cv::Mat resultOpenClose = close(open(f));
    cv::imshow("Open-Close", resultOpenClose);

    cv::Mat resultCloseOpen = open(close(f));
    cv::imshow("Close-Open", resultCloseOpen);

    cv::waitKey(0);
    cv::destroyAllWindows();

    return 0;
}
```

Make sure to adjust the file path "input_image.jpg" to your actual image file path. This code uses OpenCV to read, process, and display the images.

### Detection of Isolated Point-code

Here is the equivalent C++ code using OpenCV for the point detection function:

```cpp
#include <opencv2/opencv.hpp>

cv::Mat pointDetection(const cv::Mat& f, int thr) {
    int w = f.cols;
    int h = f.rows;

    cv::Mat g = cv::Mat::zeros(f.size(), CV_8U);

    for (int y = 1; y < h - 1; y++)
        for (int x = 1; x < w - 1; x++)
            if (std::abs(f.at<uchar>(y, x + 1) + f.at<uchar>(y, x - 1) + f.at<uchar>(y + 1, x) + f.at<uchar>(y - 1, x) - 4 * f.at<uchar>(y, x)) > thr)
                g.at<uchar>(y, x) = 255;
            else
                g.at<uchar>(y, x) = 0;

    return g;
}

int main() {
    cv::Mat f = cv::imread("input_image.jpg", cv::IMREAD_GRAYSCALE);

    if (f.empty()) {
        std::cerr << "Error: Could not read the image." << std::endl;
        return -1;
    }

    cv::imshow("f", f);

    cv::Mat result = pointDetection(f, 64);
    cv::imshow("Point Detection (thr=64)", result);

    cv::waitKey(0);
    cv::destroyAllWindows();

    return 0;
}
```

Make sure to replace "input_image.jpg" with the actual path to your image file. This code uses OpenCV to read, process, and display the images. The `pointDetection` function performs the point detection operation based on the provided threshold (`thr`).

### Marr-Hildreth edge detector-code

```cpp
#include <iostream>
#include <opencv2/opencv.hpp>
using namespace std;
using namespace cv;

void MarrHildrethEdge(const Mat& srcImage,Mat& dstImage,int kSize,double sigma)
{
    //计算卷积核
    int kernel_dia = kSize*2 + 1;
    Mat kernel(kernel_dia,kernel_dia,CV_64FC1);
    for(int i = -kSize;i<=kSize;i++)
    {
        for(int j=-kSize;j <= kSize;j++)
        {
            kernel.at<double>(i + kSize,j+kSize) = exp(-(pow(i,2) + pow(j,2)) / (pow(sigma,2)*2))
                                                    * ((pow(i,2) + pow(j,2) - 2*pow(sigma,2))/(2*pow(sigma,4)));

        }
    }
    //设置输出参数
    Mat laplaceMat(srcImage.rows-kSize*2,srcImage.cols - kSize*2,CV_64FC1);
    dstImage = Mat::zeros(srcImage.rows-kSize*2,srcImage.cols - kSize*2,CV_8UC1);

    for(int i=kSize;i <srcImage.rows - kSize;i++)
    {
        for(int j=kSize;j<srcImage.rows - kSize;j++)
        {
            double sum = 0;
             for(int x = -kSize;x<=kSize;x++)
            {
                for(int y=-kSize;y <= kSize;y++)
                {
                    sum += srcImage.at<uchar>(i+x,j+y) * kernel.at<double>(x+kSize,y+kSize);
                }
            }
            laplaceMat.at<double>(i-kSize,j-kSize) = sum;
        }
    }
    //遍历LoG算子
    for(int i=1;i < dstImage.rows - 1;i++)
    {
        for(int j= 1;j <dstImage.cols - 1;j++)
        {
            if ((laplaceMat.at<double>(i-1,j)*laplaceMat.at<double>(i+1,j) < 0) || (laplaceMat.at<double>(i,j-1)*laplaceMat.at<double>(i,j+1) < 0)
                || (laplaceMat.at<double>(i-1,j+1)*laplaceMat.at<double>(i+1,j-1) < 0) || (laplaceMat.at<double>(i-1,j-1)*laplaceMat.at<double>(i+1,j+1) < 0) )
                dstImage.at<uchar>(i,j) = 255;
        }
    }


}
int main(int argc,char *argv[])
{

    Mat srcImage = imread(argv[1]);
    if (!srcImage.data)
    {
        cerr << "fail to load image" <<endl;
        exit(-1);
    }

    Mat grayImage,dstImage;
    cvtColor(srcImage,grayImage,COLOR_BGR2GRAY);
    MarrHildrethEdge(grayImage,dstImage,4,1.6);
    imshow("srcImage",srcImage);
    imshow("dstImage",dstImage);
    waitKey();
    destroyAllWindows();
    return 0;
}
```

### Canny edge detector-code

```C++
#include <opencv2/opencv.hpp>
#include <cmath>

cv::Mat filter2D(const cv::Mat& f, const cv::Mat& mask) {
    int w = f.cols;
    int h = f.rows;

    int M = mask.cols / 2;
    int N = mask.rows / 2;

    cv::Mat g = cv::Mat::zeros(w, h, CV_32F);

    for (int y = N; y < h - N; y++)
        for (int x = M; x < w - M; x++) {
            float sum = 0;
            for (int m = -M; m <= M; m++)
                for (int n = -N; n <= N; n++)
                    sum += f.at<float>(y + n, x + m) * mask.at<float>(N + n, M + m);
            g.at<float>(y, x) = sum;
        }

    return g;
}

cv::Mat sobel_x() {
    cv::Mat mask = (cv::Mat_<float>(3, 3) << -1, 0, 1, -2, 0, 2, -1, 0, 1);
    return mask;
}

cv::Mat sobel_y() {
    cv::Mat mask = (cv::Mat_<float>(3, 3) << -1, -2, -1, 0, 0, 0, 1, 2, 1);
    return mask;
}

cv::Mat to_float(const cv::Mat& f) {
    cv::Mat g;
    f.convertTo(g, CV_32F);
    return g;
}

cv::Mat to_byte(const cv::Mat& f, double a, double b) {
    cv::Mat g;
    cv::convertScaleAbs(f, g, a, b);
    return g;
}

cv::Mat g_mask(double r) {
    int M = static_cast<int>(3 * r);
    if (M < 1) M = 1;
    int N = M;

    cv::Mat mask(2 * M + 1, 2 * N + 1, CV_32F);

    for (int n = -N; n <= N; n++)
        for (int m = -M; m <= M; m++)
            mask.at<float>(m + M, n + N) = std::exp(-(m * m + n * n) / (2 * r * r));

    float s = 0;
    for (int n = -N; n <= N; n++)
        for (int m = -M; m <= M; m++)
            s += mask.at<float>(m + M, n + N);

    for (int n = -N; n <= N; n++)
        for (int m = -M; m <= M; m++)
            mask.at<float>(m + M, n + N) /= s;

    return mask;
}

cv::Mat get_mag(const cv::Mat& gx, const cv::Mat& gy) {
    cv::Mat g;
    cv::magnitude(gx, gy, g);
    return g;
}

cv::Mat get_dir(const cv::Mat& gx, const cv::Mat& gy) {
    cv::Mat g;
    cv::phase(gx, gy, g);
    return g;
}

int main() {
    cv::Mat f = cv::imread("input_image.jpg", cv::IMREAD_GRAYSCALE);
    cv::imshow("f", f);

    // Step 1
    cv::Mat g = filter2D(to_float(f), g_mask(2));
    cv::imshow("g", to_byte(g, 1, 0));

    // Step 2
    cv::Mat gx = filter2D(g, sobel_x());
    cv::imshow("gx", to_byte(gx, 1, 128));

    cv::Mat gy = filter2D(g, sobel_y());
    cv::imshow("gy", to_byte(gy, 1, 128));

    cv::Mat mag = get_mag(gx, gy);
    cv::imshow("mag", to_byte(mag, 1, 0));

    cv::Mat dir = get_dir(gx, gy);
    cv::imshow("dir", to_byte(dir, 255 / (2 * 3.1416), 255.0 / 2));

    cv::waitKey(0);
    cv::destroyAllWindows();

    return 0;
}

```









