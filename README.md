### reset usb device

### compile
gcc reset_usb.c -o usbreset

### how to do
lsusb
Bus 002 Device 003: ID 0fe9:9010 DVICO
sudo ./usbreset /dev/bus/usb/002/003

### license
MIT by Jim
