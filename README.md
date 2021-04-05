# Driver For SDM845 Device Experimental

# 请普通用户*不要*使用这里的驱动，谢谢！

## Introduction
  These drivers are extracted from some devices,We are still in the experimental stage to test it completely

## Driver order for reference

1) PEP, BAM, SMMU, IOMMU, anything about PMIC, anything about SPMI and Glink, anything about GPIO, anything about I2C, SPI and UART,at this stage, touchscreen will be available if you provide a driver.

2) Subsystems, Reset Notifier, Subsystem blobs, DSP,blobs need to be replaced by Android ones, maybe patch is needed

3) GPU, audio, Wi-Fi, LTE, maybe other things

4) Other things


## Credits
Thanks to @imbushuo for guidance!
