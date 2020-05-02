# raspberry_pi4
This Tutorial is for setting virtual environment




### download python 3.5 environment
    wget https://www.python.org/ftp/python/3.5.6/Python-3.5.6.tar.xz
    tar xf Python-3.5.6.tar.xz
    cd Python-3.5.6
    ./configure
    make
    sudo make altinstall


## 以下會以中文說明
raspberry pi 在裝套件的過程中很容易產生很多不可預期的問題，因此在這邊為了避免一些安裝上面的問題，所以在這邊會做紀錄讓大家能方便安裝

### 操作前務必要
進入sudo(重要!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!) 

    sudo su -  
    sudo apt-get update && sudo apt-get upgrade
### opencv 
    sudo apt install libqt4-test
    sudo apt-get install -y festival python-dev python-opencv python-pip x11vnc liblivemedia-dev libv4l-dev cmake python-matplotlib vlc libatlas-base-dev libjasper-dev libqtgui4 python3-pyqt5
    pip install opencv-python
    pip install opencv-contrib-python==4.1.0.25

### 熱感應 Thinkerforge
    https://www.tinkerforge.com/en/doc/Downloads.html#downloads-tools
    下載 Brick Daemon  ==> Unix(armhf)
    下載 Brick Viewer  ==> Linux
