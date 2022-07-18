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
