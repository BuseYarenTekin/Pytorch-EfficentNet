## Step By Step PyTorch ErfNet

**Attention❗️** 
* Compatible Python Version: python==3.6.12
* IDE: Anaconda Cloud & Conda Prompt
    
    -Anaconda Cloud: https://www.anaconda.com

🔺 **Step 1:** Compatible with Python 3.6 version, a virtual environment named maskrcnn is created in conda prompt.
>conda create -n pytorch python=3.6.12

🔺 **Step 2:** The maskrcnn virtual environment is activated.
>conda activate pytorch
 
🔺 **Step 3:** Clone the Github Repository.
>git clone https://github.com/xiaoyufenfei/Efficient-Segmentation-Networks.git

🔺 **Step 4:** Setup Pytorch=1.1.0
>conda install pytorch==1.1.0 torchvision==0.3.0 -c pytorch

🔺 **Step 5:** The requirements.txt file will load the libraries needed for your project in batch.
>pip3 install -r requirements.txt

**Library and Versions to Install**

cycler==0.10.0
kiwisolver==1.1.0
matplotlib==3.1.1
numpy==1.15.0
Pillow>=6.2.2
pyparsing==2.4.2
python-dateutil==2.8.1
pytz==2018.4
six==1.12.0
torch==1.1.0
torchvision==0.3.0
torchsummary==1.5.1

🔺 **Step 6:** 
mkl-fft 1.2.0 requires numpy>=1.16

>pip install numpy==1.16.0