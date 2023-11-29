<p align="center"><a href="https://ibb.co/93LxDrW"><img src="https://i.ibb.co/NnP0vyK/blackbuntu2310.png" alt="blackbuntu2310" border="0" width="50%" height="50%"></a></p>

##
This is a fully themed installation build script to convert Ubuntu 23.10 to Blackbuntu 23.10 and best to run on a new clean installation. 

Download the latest 23.10 Build ISO from here: `https://ubuntu.com/download/desktop`

(Note this script and theme will not work correctly on older builds of ubuntu, such as 22.04 LTS, check this repo for one for 22.04 - https://github.com/andrewpayne68/BLACKBUNTU.2204)
##

```
sudo apt-get -y install git
```
```
git clone https://github.com/andrewpayne68/blackbuntu.2310.git
```
```
cd blackbuntu.2310
```
```
tar -xf blackbuntu-2310.tar.xz
```
```
cd blackbuntu-2310 && ./build.sh
```

OR run the all-in-one bash command
```
sudo apt-get -y install git && git clone https://github.com/andrewpayne68/blackbuntu.2310.git && cd blackbuntu.2310 && tar -xf blackbuntu-2310.tar.xz && cd blackbuntu-2310 && ./build.sh
```



 > After the first reboot, run 
 > ```
 > sudo nala update && sudo nala upgrade -y
 > ```
 > to update the system




![image-1](https://github.com/andrewpayne68/BLACKBUNTU.2310/blob/main/Blackbuntu-desktop-2310.PNG)


