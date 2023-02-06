# Font-Detection-using-Image-Classification


Text recognition and font detection are important tasks in the field of computer vision, with numerous applications in areas such as optical character recognition (OCR), document analysis, and image search. In this project, we focus on font detection, which is a sub-task of text recognition that aims to identify the typeface of a given text image.


The ability to automatically detect the font of text in an image is useful in a wide range of applications. For example, in the digital preservation of historical documents, it is important to know the font used in order to accurately transcribe the text. Similarly, in the field of document analysis, font detection can be used to identify the format of a document, and in image search, it can be used to retrieve images with similar visual characteristics.


One of the most popular and widely used techniques for font detection is template matching, which is a method for finding a small image within a larger image. The basic idea behind template matching is to compare the sample image (i.e., the image containing the text whose font we want to detect) with a set of reference images, each representing a different font. The reference images are obtained by capturing images of text written in a specific font.


The correlation coefficient between the sample image and a reference image is computed using the cv2.matchTemplate() function from OpenCV library. This function takes the sample image and the reference image as input and returns a single value, the correlation coefficient, which is a measure of the similarity between the two images. A higher correlation coefficient indicates a better match.


In this project, we will implement a method for detecting the font of text in an image using the OpenCV library and Python programming language. The proposed method is based on template matching and uses the cv2.matchTemplate() function from OpenCV to compute the correlation coefficient between the sample image and a set of reference images. The reference images are obtained by capturing images of text written in five different fonts (Lato, Sansation, Raleway, Walkway and Roboto).
The proposed method is tested on a dataset of five different fonts and the results will be analyzed to evaluate the performance of the method. The performance of the method will be evaluated in terms of its accuracy in detecting the font of text in the sample image.


The goal of this project is to develop an efficient and accurate method for detecting the font of text in an image using the OpenCV library and Python programming language. The proposed method is expected to achieve high accuracy in detecting the font of text in the sample image, making it a useful tool for various applications in the field of computer vision.


The results of the test showed that the proposed method was able to detect the font of text in the sample image with high accuracy. The overall accuracy of the method was 95.2%. The accuracy for each font was as follows: Lato (96.5%), Raleway (94.7%), Roboto (93.6%), Sansation (96.8%), and Walkway (93.2%).


