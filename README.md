# Image Segmentation
A small java program that demonstrates the image segmentation algorithms: Mean Thresholding and Histogram Thresholding.

## Requirements
- To run the program, you will need java version "1.8.0_301". Previous versions may not work.
- You will also need the following libraries which should come with the default JDK:
    import java.io.File;
    import java.io.IOException;
    import java.awt.image.BufferedImage;
    import java.awt.Color;
    import javax.imageio.ImageIO;
    import java.util.Scanner;

## INSTRUCTION ON USE
1. Navigate to home directory (ImageSegmentation)
2. Run "javac ImageSegmentation.java" to compile java program
3. Run "Java ImageSegmentation to run program
4. Enter image name without file type (e.g. If you want to run cathedral-LC-95.jpg, type in "cathedral-LC-95")
5. Choose a segmentation algorithm or both by typing in the number asasociated on the list when prompted.

### Histogram Algorithm
6a. When the histogram algorithm gets chosen, the program will prompt you to choose a pixel coordinate (x, y). Enter a valid pixel for x, and then afterwards, y as instructed.

### Mean Algorithm
6b. No input is needed to run this algorithm

7. After the algorithms have been processed, the program will output the duration it took to process the image in seconds. The histogram algorithm will also display how many loops it needed to stabalize the threshold value.

## Processed images
- Processed images will be found in the images folder.
- Images will be marked with either "--HISTO" or "--MEAN" depending on algorithm used.
    Examples: 
    - cathedral-LC-95.jpg
        - will be called cathedral-LC-95-HISTO.jpg when histogram algorithm is used.
        - will be called cathedral-LC-95-MEAN.jpg when mean algorithm is used.
