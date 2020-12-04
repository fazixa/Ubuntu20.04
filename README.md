# Ubuntu20.04
I installed and reinstalled Ubuntu frequently and I went through a lot of trouble installing some packages. So I'm documenting every thing and every step that worked for me so I can have them all together for my convienec.

## Essentials


```
sudo apt update
sudo apt upgrade

wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome-stable_current_amd64.deb

sudo snap install --classic code 

sudo apt install git

Sudo apt-get install openconsudo opennnect

sudo apt-get curl
 
```



<br><br>

## Python Packages
```
sudo apt install python3-pip
sudo apt install python2
curl https://bootstrap.pypa.io/get-pip.py --output get-pip.py
sudo python2 get-pip.py

pip install virtualenv

```


#### OpenCV
```
sudo pip install opencv-contrib-python   #for full modules
or
pip install opencv-python  #for main modules
```

#### dlib
```
sudo apt-get update
sudo apt-get install build-essential cmake
sudo apt-get install libopenblas-dev liblapack-dev 
sudo apt-get install libx11-dev libgtk-3-dev
sudo apt-get install python python-dev python-pip
sudo apt-get install python3 python3-dev python3-pip
```
```
pip install numpy
pip install dlib
```

