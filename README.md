# Implementation of a Surround View Camera System on NVIDIA Jetson

This project implements a surround-view image stitching system using 6 Arducam cameras connected to an NVIDIA Jetson board. The system captures synchronized images and stitches them into a single panoramic view.

## 📷 Functional Block Diagram

<img src="https://github.com/user-attachments/assets/5faf5890-d0f6-4e7b-94cc-ba4ccf793ae7" width="700">

## 🚀 Features
- High-res image capture using GStreamer and Arducam on Jetson
- Stitching using OpenCV with fallback to AKAZE + Homography
- Panorama saved to disk and previewed in real-time
- Supports 6-camera surround configuration

## 🛠️ Setup

### Hardware
- NVIDIA Jetson AGX Orion
- Arducam CSI cameras x6

### Software Dependencies

Install required Python packages:
```bash
pip3 install -r requirements.txt
