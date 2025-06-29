# O-Ring Size Detection System
![Status](https://img.shields.io/badge/Status-Development-brightgreen)

## <a href="https://oring-recognition-vite.onrender.com" target="_blank">https://oring-recognition-vite.onrender.com</a>


A real-time computer vision system for measuring O-ring dimensions using YOLOv5 object detection and camera calibration.

<!--![Screenshot](https://cdn.glitch.global/79283f6f-ef1e-4285-822b-eaefe68c462e/orning.jpg?v=1751228266800)-->
<div align="center">
  <img src="https://cdn.glitch.global/79283f6f-ef1e-4285-822b-eaefe68c462e/orning.jpg?v=1751228266800" height="1000">
</div>
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


