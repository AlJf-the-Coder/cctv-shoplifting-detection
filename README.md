# Leveraging 3D CNNs for Enhanced Shoplifting Detection in Surveillance Footage

This is our implementation of a real-time CCTV shoplifting detection system.

## Dataset

We used the videos in the shoplifting category of the [UCF-Crime Dataset](https://www.crcv.ucf.edu/projects/real-world/). 

## Preprocessing

Each video was split into 4 second clips using FFmpeg. The clips were then overlayed with pose information using the YOLOv11 model

## Model

Frames of the updated clip are then used as input to a 3D CNN which outputs the shoplifting probability of the entire clip
