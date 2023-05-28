# DigitalNAAT-Deep-Learning
Code to train and deploy Deep Learning model for digital RT-RPA-CRISPR fluorescence image analysis
# How to reproduce
You have to options:
# 1. Deploy only, i.e., use the trained weights to analyse image using your personal computer:
In this case, go to the Deploy folder and download the trained weights (best150epochondatasetv5_mAP_99_55) and codes in the Deploy folder. Then modify paths in the digitalCRISPRwholepipelineonlabtopv2-onLenovolaptop.ipynb notebook (e.g., using JupyterLab launched via Anaconda) and run. You may need to clone yolov5 (git clone https://github.com/ultralytics/yolov5) and install some libraries (e.g., using Anaconda) to your computer before deployment. There are several sample images in the Sample Images folder for you to try. Result of a sample image is shown below:
<img width="664" alt="image" src="https://github.com/hoanbklucky/DigitalNAAT-Deep-Learning/assets/20608059/fd5d8ed0-8b58-4a65-8935-50651517ef3a">

# 2. Retrain and Deploy, i.e., retrain the model to improve accuracy or retrain on your custom data before deployment:
In this case, go to the Training folder and upload the code to Google Colab and train (see image below for training result after 150 epochs). Ater training, download weights and deploy (see option 1).
<img width="749" alt="image" src="https://github.com/hoanbklucky/DigitalNAAT-Deep-Learning/assets/20608059/32663c73-1b7b-4e3b-bdce-e4bf304611c1">

For more info about the Deep Learning model and its application, see https://www.medrxiv.org/content/10.1101/2023.05.12.23289911v1
More results of other sample images:
# Sample image 1 Input and Output
![2023_03_07 06_08_00 PM](https://github.com/hoanbklucky/DigitalNAAT-Deep-Learning/assets/20608059/50b84881-448f-4453-8644-f950b2c6e383)
![output_image](https://github.com/hoanbklucky/DigitalNAAT-Deep-Learning/assets/20608059/c60d745f-f6b9-4466-8a0f-a75ba384ce02)

# Sample image 2 Input and Output
![2023_03_07 06_18_00 PM](https://github.com/hoanbklucky/DigitalNAAT-Deep-Learning/assets/20608059/201e374c-a9af-47e2-861d-9b82751cb146)
![output_image](https://github.com/hoanbklucky/DigitalNAAT-Deep-Learning/assets/20608059/096dadf5-4a27-47bf-a16c-2c9cd36e220d)

# Sample image 3 Input and Output
![2023_03_07 06_33_01 PM](https://github.com/hoanbklucky/DigitalNAAT-Deep-Learning/assets/20608059/228e7e96-1e47-4570-b96f-bdda8628dceb)
![output_image](https://github.com/hoanbklucky/DigitalNAAT-Deep-Learning/assets/20608059/39f0f1e3-b04c-4951-b1ca-b012cd764244)

# Sample image 4 Input and Output
![2023_03_07 07_03_01 PM](https://github.com/hoanbklucky/DigitalNAAT-Deep-Learning/assets/20608059/89e2c915-da1d-46c0-81e2-034fb95d5c21)
![output_image](https://github.com/hoanbklucky/DigitalNAAT-Deep-Learning/assets/20608059/fd1369ed-53e1-414c-b228-a90b45db95e6)

