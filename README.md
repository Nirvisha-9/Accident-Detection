# Accident-Detection
Real-time road accident detection using CCTV and computer vision. Uses Mask R-CNN and object tracking to detect collisions and anomalies. Sends instant notifications with vehicle details and location to emergency services via Twilio, reducing response time and improving road safety.
# Road Accident Detection and Notification System

## Overview
This project implements a **real-time road accident detection system** using CCTV surveillance and computer vision techniques. It leverages **Mask R-CNN** for accurate vehicle detection and a centroid-based tracking algorithm to monitor vehicle trajectories. Anomalies in speed and movement are used to detect potential accidents automatically.

Upon detection, the system sends **instant notifications** with accident details and location to emergency services via **Twilio SMS**, reducing response time and potentially saving lives.

## Features
- Real-time accident detection from video feeds
- Automated vehicle tracking and trajectory analysis
- Instant notification to emergency services with vehicle and location details
- High detection accuracy in diverse conditions: daylight, low visibility, rain, hail, and snow
- Can be extended to monitor traffic violations and generate automatic challans

## Technologies Used
- **Python**
- **TensorFlow & Keras**
- **OpenCV**
- **Google Colaboratory**
- **Twilio**

## How It Works
1. **Video Capture**: CCTV footage is collected from traffic cameras.
2. **Object Detection**: Vehicles are detected using Mask R-CNN.
3. **Trajectory Tracking**: Vehicle positions and movements are monitored using a centroid-based tracking algorithm.
4. **Accident Detection**: Anomalies in speed or trajectory after collisions trigger accident detection.
5. **Notification**: Emergency services are immediately notified with accident details and location via SMS.

## Applications
- Traffic surveillance at intersections and highways
- Faster emergency response to reduce fatalities
- Data-driven accident analysis for better traffic management
- Potential to extend for traffic violation detection (overspeeding, no helmet, etc.)

## Motivation
Emergency response is critical in reducing fatalities from road accidents, especially during the “golden hour” immediately after an accident. This project aims to **minimize response time** and improve safety using automated video-based accident detection.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>

   Install required dependencies:

2.  pip install -r requirements.txt


3.Run the project using a video feed or CCTV footage:

python accident_detection.py
