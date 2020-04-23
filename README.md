

## Python Wrapper for Zense SDK API

Python wrapper is an opensource project of PicoZense TOF camera API.

The goal of this project is to help developers use Zense TOF camera via python method easily.

### Requirements

- Zense library: picozense_api.dll / libpicozense_api.so
- python modules : ctypes, numpy, opencv-python(display only)

### Directory

- **linux_lib / windows_lib**: The dynamic library folder

  ```
  /libImgPreProcess.so
  /libpicozense_api.so
  ```

- **zense_cam_api.py**: zense tof wrapper code 

- **zense_cam_demo.py**: python api using demo code

### How to use

1. make sure copy the right dynamic library files to project root directory(windows do not need copy to the root directory, the code will auto add environment)
2. Run zense_cam_demo.py

User can refrence the demo code to create your project.

### FAQ:

Which version do you use?

python3.6, [PicoZense_SDK_linux](https://github.com/PicoZense/PicoZense_SDK_linux) v3.0.0.7, [PicoZense_SDK_windows](https://github.com/PicoZense/PicoZense_SDK_windows) v3.0.0.7

Which devices can this project support?

This demo only support DCAM710. If you want to use other product, you can modify the code based on different API. But there have very little difference.

