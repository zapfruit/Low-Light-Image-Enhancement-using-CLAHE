
# Low Light Image Enhacement using CLAHE 

Enhancing the quality of images captured in low-light conditions is a critical task in computer vision and image processing. This project presents a solution to improve the visibility and overall quality of such images using CLAHE, a contrast enhancement technique, applied to the RGB channels.






## Overview
CLAHE (Contrast Limited Adaptive Histogram Equalization): CLAHE is a variant of traditional histogram equalization that operates locally rather than globally. It divides the image into small tiles and applies histogram equalization separately to each tile. This adaptive approach prevents over-amplification of noise in uniform regions while enhancing local contrast.

RGB Channel Enhancement: In this project, we apply CLAHE independently to each of the Red (R), Green (G), and Blue (B) channels of the RGB image. This allows us to retain color information while improving contrast.
## Key Features

Improved Visibility: Enhance the visibility of objects and details in images captured under low-light conditions.

Reduced Noise: CLAHE's adaptive nature helps reduce noise amplification, leading to cleaner and more visually pleasing results.

Preserve Color: Applying CLAHE to RGB channels preserves the original color information in the image.
## Deployment

To deploy this project : open the .ipynb file of this project and simply click on the "open in colab" button on top. 
