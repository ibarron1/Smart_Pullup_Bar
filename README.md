# Smart_Pullup_Bar
Smart Pullup Bar based off a rasp pi 4 board

# Beam Detection
This repository contains miscellaneous code snippets.

## ToF Break Counter

`tof_break_counter.py` reads distance data from a VL53L0X or VL53L1X ToF sensor connected via I2C on a Raspberry Pi. When an object is detected closer than 20 cm, a "break" is registered. Breaks must be at least 3 seconds apart to be counted. Run the script with Python 3:

```bash
python3 tof_break_counter.py
```

The script prints the distance in millimeters and the current break count.
