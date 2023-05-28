# DigitalNAAT-Deep-Learning
Code to train and deploy Deep Learning model for digital RT-RPA-CRISPR fluorescence image analysis
# How to reproduce
You have to options:
# 1. Deploy only, i.e., use the trained weights for analyse image using your personal computer:
In this case, go to the Deploy folder and download the trained weights (best150epochondatasetv5_mAP_99_55) and codes in the Deploy folder. Then modify paths in the digitalCRISPRwholepipelineonlabtopv2-onLenovolaptop.ipynb notebook (e.g., using JupyterLab launched via Anaconda) and run. You may need to clone yolov5 (git clone https://github.com/ultralytics/yolov5) and install some libraries (e.g., using Anaconda) to your computer before deployment. There is a sample image for you to try. Result of the sample image is below:
<img width="664" alt="image" src="https://github.com/hoanbklucky/DigitalNAAT-Deep-Learning/assets/20608059/fd5d8ed0-8b58-4a65-8935-50651517ef3a">

# 2. Retrain and Deploy, i.e., retrain the model to improve accuracy or retrain on your custom data before deployment:
In this case, go to Training folder and upload the code to Google Colab and train (see image below for training result after 150 epochs). Ater training, download weights and deploy (see option 1).
<img width="749" alt="image" src="https://github.com/hoanbklucky/DigitalNAAT-Deep-Learning/assets/20608059/32663c73-1b7b-4e3b-bdce-e4bf304611c1">
