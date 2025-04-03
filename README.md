# ESRGAN
Hi there everyone Abhinav here,so here I'm gonna tell how you can run ESRGAN model in your PC.
For local machine:
>>>Make sure your system must support some graphic card and NVIDIA drivers else run the whole model in online mode
>>> download following dependencies:
FIRST OF ALL CREATE A VIRTUAL ENVIRONMENT : py -m venv <name_of_your_environment> 
# 1. Clone Repo
git clone https://github.com/xinntao/ESRGAN
# 2. Download Model 
Get model https://drive.google.com/drive/u//folders/17VYVSoZZesU6mbxz2dMAIccSS1qLecY download any one and paste it in models folder
# 3. Install Dependencies
Pip install PyTorch CUDA
just copy and paste it in your cmd terminal: pip install torch==1.13.0+cu116 torchvision==0.14.0+cu116 torchaudio==0.13.0 --extra-index-url https://download.pytorch.org/whl/cu116
Install deps pip install opencv-python glob2
# 4. Grab Low Res Image and Run Script
Place low res image in LR folder
Run python test.py 

On web browser(Using Google colab)
1) Sign up with your google account in Colab
2) Create a new notebook
3) run the following commands:
from google.colab import drive
drive.mount('/content/drive')
after that it will walk you to a sign up page just like what we did for google account and give to you a code,copy it and paste it in the notebook(if asked)..if this step is not asked don't worry it is not an error
4) Upload the ESRGAN model folder through google drive and then paste %cd '/content/drive/MyDrive/< name of your project folder>'
5) Finally run !python test.py and see the new images in result folder
               
..............................................ENJOY_THE_CODE.........................................
