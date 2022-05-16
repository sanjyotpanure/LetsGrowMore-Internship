# LetsGrowMore-Internship
**Completed task 1 and task 2 at LetsGrowMore as a data science intern.**

## Task 1 &nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sanjyotpanure/LetsGrowMore-Internship/blob/main/Image_to_Pencil_Sketch.ipynb)
We need to read the image in RBG format and then convert it to a grayscale image. This will turn an image into a classic black and white photo. Then the next thing to do is invert the grayscale image also called negative image, this will be our inverted grayscale image. Inversion can be used to enhance details. Then we can finally create the pencil sketch by mixing the grayscale image with the inverted blurry image. This can be done by dividing the grayscale image by the inverted blurry image. Since images are just arrays, we can easily do this programmatically using the divide function from the cv2 library in Python.

### Input Image 
<table>
  <tr align="center">
    <td>Original Image</td>
     <td>Converted to grey scale image</td>
  </tr>
  <tr>
    <td><img src="https://github.com/sanjyotpanure/LetsGrowMore-Internship/blob/main/images/Original_Image.png" width=600 height=300></td>
    <td><img src="https://github.com/sanjyotpanure/LetsGrowMore-Internship/blob/main/images/Grey_Scale_Image.png" width=600 height=300></td>
  </tr>
  <tr align="center">
    <td>Inverting the grey scale image</td>
     <td>Output Image - Pencil Sketch</td>
  </tr>
  <tr>
    <td><img src="https://github.com/sanjyotpanure/LetsGrowMore-Internship/blob/main/images/Invert_Grey_Scale.png" width=600 height=300></td>
    <td><img src="https://github.com/sanjyotpanure/LetsGrowMore-Internship/blob/main/images/Output_Image_Pencil_Sketch.png" width=600 height=300></td>
  </tr>
</table>


## Task 2 &nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sanjyotpanure/LetsGrowMore-Internship/blob/main/Decision_Tree_Classifier.ipynb)
Creating a Decision Tree classifier and visualize it graphically. The purpose is if we feed any new data to this classifier, it would be able to predict the right class accordingly.

### Output
<div align="center">
    <img src="https://github.com/sanjyotpanure/LetsGrowMore-Internship/blob/main/images/Decision_Tree_Output.png" width=800 alt="Screenshot" />
</div>
