# Metube
# YouTube Downloader (CustomTkinter & yt-dlp)

A modern, lightweight desktop application for downloading YouTube videos and audio. Built with Python, **CustomTkinter** for a clean user interface, and **yt-dlp** for fast and reliable downloading. 

This project solves common issues with high-resolution YouTube downloads by automatically integrating and utilizing **FFmpeg** to merge separate video and audio tracks, ensuring full compatibility with default Windows media players.
Project is created by ai

## Features

- **Modern GUI:** Clean, light-themed, and responsive interface built with CustomTkinter.
- **High-Resolution Support:** Download videos in various qualities: Best available, 4K (2160p), 1080p, and 720p.
- **Audio Extraction:** Option to download videos as MP3 audio files.
- **Windows Audio Fix (Opus to AAC):** Automatically converts unsupported audio tracks (like Opus) to AAC during the download process. This guarantees that downloaded MP4 files will play perfectly with sound in the default Windows Media Player.
- **Asynchronous Downloading:** Uses Python's `threading` so the GUI never freezes while a download is in progress.
- **Live Progress:** Real-time download progress tracking directly in the application window.
- **Standalone Build Ready:** Fully configured to be compiled into a single `.exe` file (with FFmpeg bundled inside) using PyInstaller.

## Prerequisites

To run this project from the source code, you need Python installed on your system along with a few dependencies.

1. Install the required Python libraries:
   pip install customtkinter yt-dlp
