# FOR UCSD HACKATHON, YOU CAN ACCESS MORE DATA AT:

https://app.box.com/s/55wzvodkxiwllncnh1bkk147zbxm4l68

# VOiCES
Voices Obscured in Complex Environmental Setting ([VOiCES](https://voices18.github.io/)) is an open source audio corpus put together by Lab41 and SRI International. This dataset provides audio data recorded in real acoustically challenging reverberant environments. The foreground speaker is replayed speech from Libri Speech, and distractor noise, played simulataneously was taken from MUSAN. Data is recorded in real rooms, providing recording of real reverb and additional background noise (HVAC systems, flourecent light humming, people walking outside room, etc.). For more information visit [VOiCES](https://voices18.github.io/) official site, where you can find information on how to download the full dataset.

This repo hosts a subset of the data where the main foreground speaker is at the 90 degree position. We also include a data file that has extracted spectral features.

# VOiCES-Workshop

Title: Machine Learning with realistic audio data using pandas and sci-kit learn.

Description: In this jupyter notebook workshop, we will learn how to identify a speaker's gender from realistic audio data using pandas and sci-kit learn. We will go through a brief description of VOiCES data, how to view and manipulate data in Pandas, and how to train a simple model in sci-kit learn.

Requirements:
- Jupyter notebook
- Pandas
- numpy
- matplotlib
- seaborn
- librosa
- sklearn

If you haven't yet, please install [Anaconda](https://www.anaconda.com/download/#download) on your machine.

Prerequisites for participation (Steps A to D):
A. Install Python & Jupyter Notebook if you don’t already have them:
Let's set up our Python environment via Anaconda. We'll be running through the instructions for Mac OS, but the instructions for Windows and Linux systems should be very similar. Simply follow the same installation steps as described below, and follow Anaconda's recommended installation procedures.
Mac OS specific installation and setup: https://docs.anaconda.com/anaconda/install/mac-os
Windows specific installation and setup: https://docs.anaconda.com/anaconda/install/windows
Linux specific installation and setup: https://docs.anaconda.com/anaconda/install/linux
Mac OS setup
Step 1: Go to the Anaconda download page and download the appropriate installer. We recommend installing the Python 3 version.
Installation requires about 600M of space. If you're tight on space, you can try miniconda.
Step 2: Follow Anaconda's recommended installation instructions, making note of the directory where Anaconda lives (you should be prompted to specify this, your home directory is a good choice).

B. In Terminal, install required packages:
pip install pandas numpy matplotlib seaborn librosa sklearn

C. Clone the workshop repo:
cd {your gitrepos folder}
git clone https://github.com/Lab41/VOiCES-subset

D. Run the notebook:
jupyter notebook
