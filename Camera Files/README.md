# Camera File Installation

LabView stores their camera files under C:\Users\Public\Documents\National Instruments\NI-IMAQ\Data

Copy the *.icd files found in this repository into this folder.

# Configuring Camera

Once the *.icd files are in the correct folder you can configure the camera with them by:

1. Launch NI-MAX
2. Navigate to the camera ( My System > Devices and Interfaces > NI PCIe-1433 "img0"
3. Right click "Channel 0" and select Camera > Wasatch > (your *.icd file)
4. **If the camera file does not immediately appear in MAX, you will need to right click on the camera and select Open Camera, then target the newly installed icd file. **

