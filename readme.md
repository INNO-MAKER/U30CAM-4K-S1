# U30CAM-4K-S1:

## Hardware 

For hardware please refer to the user manual

## Software 

For software please refer to below link :

[UVC Camera Software](https://github.com/INNO-MAKER/UVC-Camera-Software)



## FAQ

Q1： Why does the actual tested frame rate not reach the frame rate described in the datasheet?

A1:   

(1) **Insufficient USB port bandwidth or power supply**: If the USB port bandwidth or power supply is inadequate, it can affect the device's performance. Plug the camera module directly into the computer's USB port to avoid sharing bandwidth with other devices, or use a USB hub with external power supply. 

(2)**Insufficient CPU/MPU/GPU/RAM performance**: This issue is common with o8lder computers or ARM development boards. Older hardware may struggle to process image data quickly, causing the frame rate to fall short. Consider upgrading the hardware platform or reducing the resolution to alleviate the system's load.

(3)**Driver or testing software issues**: This is less common, but if the first two causes are ruled out and the issue persists, consider updating the UVC drivers or switching to another testing software.







