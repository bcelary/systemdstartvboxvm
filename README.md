# systemdstartvboxvm
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

Supporting files for the blog article about starting a VirtualBox VM on boot with Systemd. Refer to [this blog article](https://www.pragmaticlinux.com/2020/10/start-a-virtualbox-vm-on-boot-with-systemd/) on the PragmaticLinux blog for detailed instructions on how to use the files in this repository.

```
sudo wget -P /etc/systemd/system/ https://raw.githubusercontent.com/bcelary/systemdstartvboxvm/main/source/vbox_vm_start%40.service
VBoxManage list vms
sudo systemctl enable vbox_vm_start@<name of VM with no spaces!>
```
