# O-Ring Size Detection System
![Status](https://img.shields.io/badge/Status-Development-brightgreen)

![Status](https://img.shields.io/badge/Status-Development-brightgreen)

<!--[![Demo Video](https://img.shields.io/badge/Demo-Video-blue)](https://example.com/demo) 
[![Live Demo](https://img.shields.io/badge/Live-Demo-green)](https://yourdeployment.com)-->

A real-time computer vision system for measuring O-ring dimensions using YOLOv5 object detection and camera calibration.

![Screenshot](./public/screenshot.png)

## Key Features

- **Precision Measurement**: Detects O-rings with ±0.1mm accuracy after calibration
- **Defect Classification**: Identifies 6 defect types (SCAR, TEAR, BLOCK, etc.)
- **Cross-Device**: Works on mobile/desktop browsers with camera access
- **Optimized Inference**: WebWorker + ONNX Runtime for smooth 15 FPS performance
- **Calibration System**: Reference object scaling for physical measurements

## Technical Stack

| Component               | Technology                          |
|-------------------------|-------------------------------------|
| Frontend                | React, TensorFlow.js                |
| Computer Vision         | YOLOv5 (custom-trained ONNX model)  |
| Real-time Processing    | Web Workers, WebGL                 |
| Camera Pipeline         | MediaDevices API                    |
| Measurement System      | Perspective calibration             |

## Installation

```bash
git clone https://github.com/yourusername/o-ring-detector.git
cd o-ring-detector
npm install
npm start
