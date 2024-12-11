# rtspeckle
Using FLIR's SDK to create a real-time Laser Speckle Contrast software 

### Downloading pyton 
Since this repo uses GPU accelerated processes, I will be telling you how to download python for windows 10/11. Linux will come eventually 

To use this repo you must have download Python in your computer. 

You can download using the link https://www.python.org/downloads/release/python-3810/ which would allow you to download python 3.8.10 which is the verion this repo uses 
Note: you can download the newest version of python here https://www.python.org/. WE will set a virtual environment regardless so you can go by with downloading the newest version 

You can then dowload like any executable files. 

Do not forget to add python to path, this will tell windows to create a shortcut so that you can launch python from command prompt.
Note, Make sure you don't have many versions of python in path

### Downloading python using command prompt 

Open command prompt by pressing **Win + R** and typing **cmd**, then press enter. 
Change your dirctory by typing __cd C:\Users\user\Downloads__ which will take you to the Downloads directory 
Note: the user should have been set by you and you can check by looking at the path for the downloads folder or the documents folder if this is easier for you 

Run the following command: **python-3.x.x.exe /quiet InstallAllUsers=1 PrependPath=1**.
For the purposes of this repo, you would be ok with installing the newest version (for December 2024) by changing the x.x in python-3.x.x with 12 and 10 respectivelly. Else, you can use the Python version for this repo which is 3.8.10 

## downloading pip and Creating a virtual environment 
Note: You may want to create a new file in whichever path you would prefer, either in windows file explorer or using command prompt by going to a specific path (most likely being under documents) by typing **cd C:\Users\user\Documents** and then typing **mkdir \new project** (you can name it whichever name you must. Also, if you downloaded pytnon 3.4 and on (which you should) you already have pip installed in your system alongside Python 

pip is a package installer that allows to install different libraries in an easier and efficient manner. You can download and install it from this page: https://pypi.org/project/pip/ and follow the instructions. 
OR you can open command prompt and download pip by typing: **curl https://bootstrap.pypa.io/get-pip.py -o** which will download the installer. Next, you will want to run the installer bby typing **python get-pip.py**. Finally you can verify the installation and your version of pip by typing **pip --version**

create Pytnon environment:
Navigate to the project directory by typing the following prompt in command prompt: cd/path/to/project.
Create a virtual environment using venv: pyton --m venv env (where env is you new environemt name. 
Activate the virtual environment: env\Scripts\activate. 



