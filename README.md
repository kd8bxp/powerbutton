# powerbutton
This is a remote power controller for Raspberry Pi 3 mode B.
# How to setup.
# You should make sure you have wiringPi and git-core installed before you git clone the repository!
## sudo apt-get install -y wiringPi
## sudo apt-get install -y git-core
## cd ~
## git clone https://github.com/yoyojacky/powerbutton.git 
## sudo mv ~/powerbutton/gpioshutdown /etc/init.d/
## sudo chmod +x /etc/init.d/gpioshutdown
## sudo vim.tiny /etc/rc.local
add this two lines before exit 0
## gpio mode 25 out 
## gpio write 25 1 
### [optional]
You can modify your /boot/config.txt file as config.txt.
### have fun
