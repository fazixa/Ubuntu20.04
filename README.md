# Ubuntu20.04
I installed and reinstalled Ubuntu frequently and I went through a lot of trouble installing packages. So I'm documenting every thing and every step that worked for me for my convienec.

## Essentials
`sudo apt update`
`sudo apt upgrade`

### chrome 
```
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome-stable_current_amd64.deb
```

### VS Code
`sudo snap install --classic code `







## Python Packages
`sudo apt install python3-pip`


#### OpenCV
`sudo pip install opencv-contrib-python`
> for full modules
or
`pip install opencv-python`
> for main modules

