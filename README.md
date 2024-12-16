# Leveraging 3D CNNs for Enhanced Shoplifting Detection in Surveillance Footage

This is our implementation of a real-time CCTV shoplifting detection system.

## Dataset

We used the videos in the shoplifting category of the UCF-Crime Dataset. 

## Preprocessing

Each video was split into 4 second clips using FFMPEG. The clips were then overlayed with pose information using the YOLOv11 model
