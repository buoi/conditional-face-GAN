# conditional-face-GAN
Attribute conditional face generation with ACGAN in keras; GPU computation of FID and attribute metrics.  
In depth description here: [project_report.pdf](project_report.pdf).

<img width="1089" alt="ACGAN 10 attributes results" src="https://user-images.githubusercontent.com/38630200/163162710-b067b9f0-042c-492e-b1d1-24ea8a8ab11f.png">



`attribute_conditional_gan.ipynb`  
is a self contained notebook for the training of models with different image resolution and number of attributes .

`evaluate_GAN.ipynb`  
keeps the code for evaluation of trained models and plotting images with relative attributes.

`GAN_Attribute_Classifiers.ipynb`
has the code for training the MobilenetV2 attribute classifiers used to evaluate the GAN models with Accuracy and F1 score.

