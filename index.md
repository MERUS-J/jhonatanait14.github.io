---
layout: "default"
title: "🎤 dictate.sh - Quick and Easy Speech Transcription"
description: "🎤 Transcribe speech in real-time with low latency using `dictate.sh`, a standalone tool for efficient, local speech recognition and intent analysis on Apple Silicon."
---
# 🎤 dictate.sh - Quick and Easy Speech Transcription

[![Download dictate.sh](https://img.shields.io/badge/Download%20dictate.sh-v1.0-blue)](https://github.com/JhonatanAiT14/dictate.sh/releases)

## 📖 Overview

`dictate.sh` provides quick and efficient speech transcription for users on Apple Silicon. This application uses advanced machine learning techniques for fast speech recognition, enabling users to convert speech into text seamlessly. With its simple setup, anyone can start talking and transcribing in no time.

## 🚀 Getting Started

To begin using `dictate.sh`, follow these steps:

1. **Download the Application**  
   You need to visit the [Releases page](https://github.com/JhonatanAiT14/dictate.sh/releases) to download the latest version of `dictate.sh`. 

2. **Install Prerequisites**  
   Make sure you have the following requirements:
   - A Mac with Apple Silicon.
   - Python version 3.10 or higher.
   - `uv` installed on your machine.
   - Microphone access granted to your terminal application.

3. **Set Up Your Environment**  
   If you do not have Python or `uv` installed, you can use a package manager like Homebrew to install them:
   ```bash
   brew install python
   pip install uv
   ```

## 📥 Download & Install

To get started, visit the [Releases page](https://github.com/JhonatanAiT14/dictate.sh/releases) and download the latest version of `dictate.sh`. After downloading, follow the instructions to set it up on your machine.

## 🎤 How to Use

Once you have `dictate.sh` installed, you can easily run it from your terminal. Here’s how:

1. **Run the Speech Transcription**  
   Open your terminal and navigate to the folder containing `dictate.sh`. Run the application using:
   ```bash
   uv run stt.py
   ```

2. **Using Intent Analysis**  
   If you want to enable intent analysis, simply add the `--analyze` flag:
   ```bash
   uv run stt.py --analyze
   ```

3. **Using Different ASR Models**  
   You can choose a different ASR model by using the `--model` flag:
   ```bash
   uv run stt.py --model mlx-community/Qwen3-ASR-1.7B-8bit
   ```

4. **List Audio Devices**  
   To see all available audio input devices on your system, run:
   ```bash
   uv run stt.py --list-devices
   ```

5. **Select a Specific Audio Device**  
   If you want to use a specific audio input device, use the `--device` option:
   ```bash
   uv run stt.py --device 3
   ```

## 🛠️ Requirements

Before using `dictate.sh`, ensure that your system meets the following requirements:

- **Operating System:** macOS on Apple Silicon.
- **Python Version:** 3.10 or higher.
- **Tools:** `uv` must be installed.
- **Permissions:** Grant microphone access to your terminal.

## 🌟 Features

- **Low-Latency Transcription:** Uses machine learning for fast speech recognition.
- **Voice Activity Detection:** Automatically detects when you are speaking, ensuring accurate transcription.
- **Intent Analysis:** Optional feature for analyzing the intent behind your speech.
- **Live Terminal Interface:** Provides real-time status updates, transcripts, and statistics.
- **Offline Functionality:** Works without internet connection after downloading required models.

## 📊 Troubleshooting

If you encounter issues while running `dictate.sh`, check the following:

- Ensure you have the correct Python version installed.
- Confirm that `uv` is properly set up on your system.
- Make sure your microphone is functioning and has permission in terminal settings.

For additional support or to report issues, visit our GitHub repository and create an issue. 

## 🔗 Learn More

Explore additional resources and documentation in the [GitHub repository](https://github.com/JhonatanAiT14/dictate.sh) to enhance your understanding and usage of `dictate.sh`. 

Remember, you can always return to the [Releases page](https://github.com/JhonatanAiT14/dictate.sh/releases) to check for the latest updates.

[![Download dictate.sh](https://img.shields.io/badge/Download%20dictate.sh-v1.0-blue)](https://github.com/JhonatanAiT14/dictate.sh/releases)