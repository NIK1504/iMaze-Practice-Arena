# iMaze-practice-Arena

* [Installation](#Installation)
* [Usage](#Usage)

## Installation

As this competition is going to be conducted in webots simulator, you may follow these instructions to install webots locally

### Windows

* Download webots setup file(shown below) from the official website - https://cyberbotics.com/

  ![win-1](images/win-1.jpg)

* Open the file and choose *Install for me only* option

  ![win-2](images/win-2.jpg)

* And then follow the prompts (*Next*, *Next*, ..., *Install*).

**Python installation :**

* Open the https://www.python.org/downloads/  in your web browser. Navigate to the Downloads tab for Windows.

* Click on the link to download **Windows x86 executable installer** if you are using a 32-bit installer. In case your Windows installation is a 64-bit system, then download **Windows x86-64 executable installer**(shown below).

  ![ver1](images/ver1.jpg)

* Once the installer is downloaded, run the Python installer.

  ![iwin](images/iwin.jpg)

* You can now start the installation of Python by clicking on **Install Now**.

### Linux

* Download .deb file (shown below) from the official website - https://cyberbotics.com/

  ![lin-1](images/lin-1.jpg)

* Go to the directory where you have downloaded the file and just double click the file. You can see something like below, just click *install*

  ![lin-2](images/lin-2.jpg)
  
**Python installation :**

* Update the packages list and install the prerequisites:

  ```
  $ sudo apt update
  $ sudo apt install software-properties-common
  
  ```

* Add the deadsnakes PPA to your system’s sources list:

  ```
  $ sudo add-apt-repository ppa:deadsnakes/ppa
  ```

* you can install Python 3.9 by executing:

  ```
  $ sudo apt install python3.9
  ```

* Verify that the installation was successful by typing:

  ```
  python3.9 --version
  ```

## Usage

Now that you have downloaded webots in your computer, you may follow these instruction to clone this repository, load the arena.

### Clone this repository

* Firstly, install git in your computer. You may follow these tutorials - [Windows](https://phoenixnap.com/kb/how-to-install-git-windows) | [Linux](https://www.atlassian.com/git/tutorials/install-git#linux)

* Then open command prompt (*in windows*) or terminal (*in linux*) and clone this repository

  ```shell
  git clone https://github.com/Robotics-Club-IIT-BHU/iMaze-practice-Arena.git
  ```

### Load the arena

* Open the webots simulator and you are expected to see a window as shown below

  ![web-1](images/web-1.jpg)

* Click on *File* then *Open World* as shown below

  ![web-2](images/web-2.jpg)

* Go to the folder where you have cloned this repository and select `PraticeArena.wbt` file as shown below

  ![web-3](images/web-3.jpg)
  
### Making a Custom Controller

* Once you have opened the World, click on Wizards -> New Robot Controller

![one](images/Custom-Controller-I.png)

* Click on Next

![two](images/Custom-Controller-II.png)

* Select **Python** and then click Next

![three](images/Custom-Controller-III.png)

* Provide a Name for your Controller

![four](images/Custom-Controller-IV.png)

* Click on Finish 

![five](images/Custom-Controller-V.png)

### Connecting your Controller to the Robot

* On the left side of the screen navigate to E-puck -> controller "PS2_controller" and then click on Select

![six](images/Connect-to-Robot-I.png)

* From the available options choose your controller and then click OK

![seven](images/Connect-to-Robot-II.png)
