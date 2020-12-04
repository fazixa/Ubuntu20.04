# Ubuntu20.04
I installed and reinstalled Ubuntu frequently and I went through a lot of trouble installing some packages. So I'm documenting every thing and every step that worked for me for my convienec and have them all together.

## Essentials
`sudo apt update`
`sudo apt upgrade`

#### chrome 
```
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome-stable_current_amd64.deb
```

#### VS Code
`sudo snap install --classic code `



<br><br>

## Python Packages
`sudo apt install python3-pip`


#### OpenCV
`sudo pip install opencv-contrib-python`

> for full modules

or

`pip install opencv-python`

> for main modules

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
pip3 install numpy
pip3 install dlib
```

