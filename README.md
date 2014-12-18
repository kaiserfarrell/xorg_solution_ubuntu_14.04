xorg_solution_ubuntu_14.04
==========================

[Solution For display problem Xorg]
Detect unknown monitor?
Ubuntu 14.04 hang/Freeze/ mouse cursor not working after install nvidia 331?
Try this
Step 0
Nvidia server setting > profile> choose intel for nvidia-optimus
reboot
Step 1
Settings>Software & Update check "Source code" "Ubuntu Software".
check all PPAs |✔| Source Code
Step 2
sudo apt-get update
Step 3
sudo apt-get build-dep xorg-server
Step 4
Download
https://github.com/…/xorg_solution_ubuntu_1…/tree/master/deb
Step 5
sudo dpkg -i xserver-common_1.15.1-kaiserfarrell.deb 
xserver-xorg-core_1.15.1-kaiserfarrell_amd64.deb
Step 6
reboot
