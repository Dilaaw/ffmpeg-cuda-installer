# FFmpeg with CUDA Installer

This bash script automates the process of installing FFmpeg with CUDA support along with all necessary dependencies on Ubuntu-based systems.

## 🚀 Quick Installation

### Direct execution from GitHub (recommended)
```bash
curl -L https://raw.githubusercontent.com/Dilaaw/ffmpeg-cuda-installer/main/setup.sh | bash
```

### Download and run locally
```bash
wget https://raw.githubusercontent.com/Dilaaw/ffmpeg-cuda-installer/main/setup.sh
chmod +x setup.sh
./setup.sh
```

## 🎯 What does this script do?

- **Dependencies Installation:** Installs essential libraries and development packages required for compiling FFmpeg and its codecs.

- **Downloading and Configuring FFmpeg:** Downloads the latest FFmpeg source code, configures it with necessary flags for CUDA support, and compiles it.

- **nv-codec-headers Installation:** Clones the nv-codec-headers repository and installs it, providing headers for Nvidia GPU accelerated video encoding/decoding.

- **Configuration and Installation of FFmpeg with CUDA:** Configures and compiles FFmpeg with CUDA support enabled, allowing for hardware-accelerated video processing on Nvidia GPUs.

## 📋 Prerequisites

Before using this script, ensure you meet the following requirements:

- **CUDA:** CUDA must be installed on your machine beforehand. You can download CUDA from the official Nvidia website.

- **Compatible GPU:** Make sure your graphics card is compatible with CUDA.

- **CUDA Toolkit and Drivers:** Before running this script, make sure you have installed all the necessary tools for CUDA. Here are the commands to install CUDA Toolkit and CUDA drivers on Ubuntu:

  ```bash
  sudo apt install nvidia-driver-{latest version}
  sudo reboot
  sudo apt install nvidia-cuda-toolkit
  ```
## ⚠️ Disclaimer

This script is tailored for Ubuntu-based systems and may not work on other distributions without modification.

Use caution when running scripts from the internet, ensure you trust the source, and review the script contents before execution.

Feel free to contribute or report issues on GitHub.

---

This README provides comprehensive information on how to use the script safely and effectively, including prerequisites, usage instructions, and disclaimers.
