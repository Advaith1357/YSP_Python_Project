# YSP_Python_Project

research question -	What technique are the most effective in increasing the complexity of captchas to mitigate machine learning solutions. 
Expected coding work to be done - 
4.	Data Collection: Collect a dataset of CAPTCHA images along with their corresponding labels. You can manually create CAPTCHA images with warped letters or use publicly available datasets.

Data Preprocessing: Preprocess the CAPTCHA images to enhance their quality and make them suitable for training. This may include resizing, normalization, noise removal, and thresholding.

Feature Extraction: Extract relevant features from the preprocessed CAPTCHA images. 
Commonly used features include pixel intensity values, edges, contours, and shape descriptors.

Model Training: Train a machine learning model on the extracted features and their corresponding labels. We will use Convolutional Neural Networks (CNNs) depending on the complexity of the problem and the size of your dataset.

CAPTCHA Solving: Use the trained model to predict the labels of new CAPTCHA images. Apply appropriate techniques to handle the warped letters, such as image warping or distortion correction.

Program CAPTCHAs: We will program techniques to add complexity to the CAPTCHAS and see if our machine model fails. Some ideas are flipping contrast, adding colors, adding background noise, rotating  and warping the letters, and blurring the letters.  

Model Evaluation: Evaluate if these techniques caused our machine learning model to fail. Measure performance metrics such as accuracy, precision, recall, and F1 score to assess the model's effectiveness and to see which techniques work the best to make captchas more secure and robot proof. 

It's important to note that CAPTCHAs are designed to be difficult for machines to solve. Therefore, achieving high accuracy in beating a warped letters CAPTCHA may require more advanced techniques like deep learning or combining multiple models.
Possible Packages to be used -	We will be using Tensorflow, Keras, opencv, scikitlearn, CAPTCHA, PANDAS, PIL, matplotlib, itertools and numpy for now. 
6.	https://wordpress.org/plugins/really-simple-captcha/
we will be using this to generate our own data set and then create python scripts to augment the original data to analyze the various effect of changes on model accuracy. 
We may also use the captcha package in Python to create our own dataset. 
7.	Adding lines in the background will cause the model accuracy to decrease the most.
8.	https://github.com/Advaith1357/YSP_Python_Project.git
