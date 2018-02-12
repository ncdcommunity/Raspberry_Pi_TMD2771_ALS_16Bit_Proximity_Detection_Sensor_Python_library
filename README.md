[![ TMD2771](TMD2771_I2C.png)](https://store.ncd.io/product/tmd2771-ambient-light-sensing-als-16-bit-proximity-detection-calibrated-to-100-mm-i2c-mini-module/).

#  TMD2771

The TMD2771 is a high sensitivity ambient light sensor (ALS) and proximity detector. The ALS has a dynamic range of up to 1,000,000:1, and is highly sensitive allowing it to work well in diverse lighting conditions, including behind dark glass. The proximity detection is calibrated to 100-mm detection. 
This Device is available from www.ncd.io 

[SKU: TMD2771]

(https://store.ncd.io/product/tmd2771-ambient-light-sensing-als-16-bit-proximity-detection-calibrated-to-100-mm-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface TMD2771 ALS and 16bit proximity detection sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/tmd2771-ambient-light-sensing-als-16-bit-proximity-detection-calibrated-to-100-mm-i2c-mini-module/">TMD2771 ALS and 16bit proximity detection sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python TMD2771.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
