# raspberry pi 4
This Tutorial is for setting virtual environment of raspberry pi4 


## rotate screen 
add this to the /boot/config.txt    
        
        display_rotate = 0 #default
        display_rotate = 1 #rotate 90 degrees
        display_rotate = 2 #rotate 180 degrees
        display_rotate = 3 #rotate 270 degrees
    


## 以下為操作虛擬環境
raspberry pi 在裝套件的過程中很容易產生很多不可預期的問題，因此在這邊為了避免一些安裝上面的問題，所以在這邊會做紀錄讓大家能方便安裝
### 操作前務必要
進入sudo(重要!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!) 

    sudo su -  
    sudo apt-get update && sudo apt-get upgrade
    
### virtualenv
    pip3 install virtualenv
### opencv 
    sudo apt install libqt4-test
    sudo apt-get install -y festival python-dev python-opencv python-pip x11vnc liblivemedia-dev libv4l-dev cmake python-matplotlib vlc libatlas-base-dev libjasper-dev libqtgui4 python3-pyqt5
    pip3 install opencv-python
    pip3 install opencv-contrib-python==4.1.0.25
### PyQt5
    pip3 install vext.PyQt5
### Keras
    pip3 install keras
### tensorflow
    pip3 install tensorflow
### PIL
    pip3 install Pillow
### tinkerforge
    pip3 install tinkerforge
### pygame
    pip3 install pygame
### 熱感應 Thinkerforge
    https://www.tinkerforge.com/en/doc/Downloads.html#downloads-tools
    下載 Brick Daemon  ==> Unix(armhf)
    下載 Brick Viewer  ==> Linux
    
### 注意事項
   1. 調整Mem for GPU 在2G最大600，超過會無法顯示
   2. 上述的install，如果是預設python是指python3以上那請改成pip

    
    
### Download python 3.5 environment
    wget https://www.python.org/ftp/python/3.5.6/Python-3.5.6.tar.xz
    tar xf Python-3.5.6.tar.xz
    cd Python-3.5.6
    ./configure
    make
    sudo make altinstall

### venv
https://docs.python.org/zh-tw/3/tutorial/venv.html




## reference
rotate screen https://pimylifeup.com/raspberry-pi-rotate-screen/
