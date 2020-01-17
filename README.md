# MicroPython hello world!

Setup python `pip3 install esptool`
(install USB drivers from here)[https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers]
(Download Firmware)[http://micropython.org/download]
upload firm ware `esptool.py --chip esp32 --port /dev/ttyUSB0 --baud 460800 write_flash -z 0x1000 esp32-20190125-v1.10.bin`
