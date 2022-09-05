# Python Wrapper for Vzense Base SDK API

Python wrapper is an opensource project of Vzense TOF camera API.

The goal of this project is to help developers use Vzense TOF camera via python method easily.

- PythonSDK version: V3.5.4.1
- VzenseBaseSDK version: V3.5.4

## Supported Devices

- DCAM710
- DCAM550U
- DCAM550P
- DCAM550E
- DCAM560C

## Requirements

- Python version : >= 3.7
- Python modules : ctypes, numpy, opencv-python(display only)

## Add Library to Python Path

```bash
echo "export PYTHONPATH=$PATH:{$PATH_TO_PACKAGE}/vzense-api:{$PATH_TO_PACKAGE}/vzense-api/DCAM550/API:{$PATH_TO_PACKAGE}/vzense-api/DCAM560/API:{$PATH_TO_PACKAGE}/vzense-api/DCAM710/API"  >> ~/.bashrc
```

## Directory

- **DCAM550**: the API and Sample code for DCAM550U/DCAM550P/DCAM550E
- **DCAM560**: the API and Sample code for DCAM560CPRO/DCAM560CLITE
- **DCAM710**: the API and Sample code for DCAM710
- **Lib**: VzenseBaseSDK dynamic library files

## Quick Start

- Step 1. install modules:

    ```bash
    pip install numpy
    pip install opencv-python
    ```

- Step 2. Go to the code folder and run the code

    ```bash
    cd {$PATH_TO_PACKAGE}/DCAM560/Samples/FrameViewer
    python3 FrameViewer_DCAM560.py
    ```
