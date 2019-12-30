# quick-ubuntu-cloud-virtualbox
Quickly setup of Ubuntu cloud in VirtualBox by using 

1. Download Ubuntu Cloud Images .vmdk format from  https://cloud-images.ubuntu.com/  or to be specific I'm using https://cloud-images.ubuntu.com/bionic/current/bionic-server-cloudimg-amd64.vmdk

2. Download user-data iso [my-seed.iso](/my-seed.iso)  from this repository. 

3. In the virtualBox, create a new VM and use the .vmdk image from (1) and set my-seed.iso from (2) as IDE master/ optical drive.

![screenshot](/img/vbox.png) 

4. Now ready to start and run the  Ubuntu Cloud in VirtualBox using username / password : ubuntu/welcome1

