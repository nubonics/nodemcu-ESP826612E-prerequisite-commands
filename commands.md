# Commands
## If the command `esptool.py` is not working, add the tool to the PATH variable in a terminal
  - ### Courtesy of https://github.com/espressif/esptool/issues/343
    - `PATH="$HOME/bin:$HOME/.local/bin:$PATH"`
  - `sudo python3 -msptool --port /dev/ttyUSB0 erase_flash`
  - `esptool.py --port /dev/ttyUSB0 --baud 115200 write_flash --flash_size=detect 0 esp8266-ota-20200421-v1.12-388-g388d419ba.bin`
