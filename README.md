# Research enviroment for Computer Vision
<p>This set of Notebooks and utils functions provides a complete set of code to be able to train and leverage custom Object Detection models using TensorFlow but we will constanting update more models type and frameworks

## Python version
sudo apt install python3-dev


## Colab setup
### Cloning repo into drive directory

Create new colab file and run: 

<pre>
from pathlib import Path
from google.colab import drive
drive.mount("/content/drive")
</pre> 

accept conection to google account

<pre>
BASE_DIR = Path(Path.cwd(), "drive/MyDrive/")
PROJECT_DIR = Path(BASE_DIR, "project_research")
!mkdir -p {PROJECT_DIR}
!git clone https://github.com/bluelabsai/cv-research.git {PROJECT_DIR}
</pre> 

## Local setup
**Steps**
<br />
<b>Step 1.</b> Clone this repository: https://github.com/bluelabsai/cv-research
<br/><br/>
<b>Step 2.</b> Create a new virtual environment 
<pre>
python3 -m venv .venv
</pre> 
<br/>
<b>Step 3.</b> Activate your virtual environment
<pre>
source .venv/bin/activate # Linux
.\.venv\Scripts\activate # Windows 
</pre>
<br/>
<b>Step 4.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install notebook
pip install ipykernel
python -m ipykernel install --user --name=venv
</pre>
<br/>
