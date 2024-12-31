# EasyQuantizationGUI

## Fork for working installation

```bat
git clone https://github.com/rainlizard/EasyQuantizationGUI.git
cd .\EasyQuantizationGUI\
D:\apps\dev\Python311\Scripts\virtualenv venv
.\venv\Scripts\activate
pip install -r .\requirements.txt
pip install torch==2.4.1 torchvision==0.19.1 torchaudio==2.4.1 --index-url https://download.pytorch.org/whl/cu124
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
```

## Original Readme

This application basically just simplifies this process: https://github.com/city96/ComfyUI-GGUF/tree/main/tools

![screenshot](https://github.com/user-attachments/assets/11d2315b-9ea4-4caf-a3a0-e211defae7a7)

Run `EasyQuantizationGUI.bat` to start the application.

Requirements:
- [Python](https://www.python.org/downloads/windows/)
- Windows (can be adjusted later to support Linux)
