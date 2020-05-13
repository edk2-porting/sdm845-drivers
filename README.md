## Driver order for reference

1) PEP, BAM, SMMU, IOMMU, anything about PMIC, anything about SPMI and Glink, anything about GPIO, anything about I2C, SPI and UART

​    At this stage, touchscreen will be available if you provide a driver.

 

2) Subsystems, Reset Notifier, Subsystem blobs, DSP

​    Blobs need to be replaced by Android ones, maybe patch is needed

 

3) GPU, audio, Wi-Fi, LTE, maybe other things

 

4) Other things

 

Thanks to @imbushuo for guidance!