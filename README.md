# Keyboard Firmware

## Build

```
# clone this repo
git clone https://github.com/ncwhale/Keyboard_Firmware.git

# Configure build
cd Keyboard_Firmware
mkdir build
cd build
cmake ..

# Then build & upload target.
make sk_v3_slave

# Need press the reset button on board.
make upload_sk_v3_slave
```