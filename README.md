# rtl88x2bu_dwa_181_driver
D-link DWA 181 driver for Linux kernel 5.0

## Already tested distro
Ubuntu 18.0.4 (4.15.0.0-20-generic)
Ubuntu 18.0.4 (5.0.0-37-generic)

## Installation
```
sudo dkms add ./rtl88x2bu_dwa_181_driver
sudo dkms build -m rtl88x2bu -v 5.6.1
sudo dkms install -m rtl88x2bu -v 5.6.1
sudo modprobe 88x2bu
```
