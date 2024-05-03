# Breast-Cancer-Detection-System
The project focuses on detecting breast cancer using mammograms, with the aim of aiding in the early 
diagnosis of the disease. Breast cancer is a significant health concern globally, with increasing cases 
prompting the need for more effective detection methods. The project aims to automate the detection 
process to facilitate early diagnosis, which can significantly improve the chances of successful 
treatment.
The project's methodology involves several steps. Initially, adaptive mean filtering is applied to the 
mammogram images to remove noise and enhance image quality. This filtering technique is chosen for 
its effectiveness in distinguishing fine details from noise. Following this preprocessing step, Gaussian 
Mixture Model (GMM) segmentation is performed to classify regions in the image. Additionally, k-means segmentation is employed to further analyze the image data.
A notable aspect of the project is the implementation of the Hidden Markov Random Field (HMRF) 
model and its Expectation-Maximization (EM) algorithm. These techniques are utilized to refine the 
segmentation results and improve the accuracy of cancer detection.
The project is implemented in MATLAB and provides a user-friendly interface (GUI) for easy 
interaction. Users can input mammogram images and follow the steps outlined in the GUI to analyze 
the images for the presence of cancer. The project draws from research literature, citing relevant studies 
that contribute to the understanding and development of the detection methodology.
Using an adaptive mean filter for breast cancer detection in mammograms offers several advantages 
over other filters, primarily due to its ability to preserve edge information while effectively reducing 
noise. Lastly, it uses Probabiltistic Neural Network to classify the 3 types of microclacifications in a breast and they are Benign, Malignant & Normal.

Important Note: - To run the project download the .exe file and install it on your PC. 
#Dataset Download Link:- https://data.mendeley.com/datasets/ywsbh3ndr8/2
#The report in pdf format contains all the information of this project & includes its screenshots too.
