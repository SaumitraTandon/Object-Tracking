# Object Tracking using OpenCV

This repository contains two Python scripts that demonstrate object tracking using different algorithms implemented in the OpenCV library: CSRT (Discriminative Correlation Filter with Channel and Spatial Reliability) and KCF (Kernelized Correlation Filters).

## Prerequisites

- Python 3.x
- OpenCV library

## Installation

1. Clone the repository:
2. Install the required dependencies:
3. Download the sample video file `race.mp4` and place it in the repository directory.

## Usage

### 1. object_tracking_CSRT.py

This script uses the CSRT algorithm for object tracking.

1. Run the script:
2. A window will open, displaying the video frames.
3. Use the mouse to select the region of interest (ROI) by drawing a bounding box around the object you want to track.
4. The script will track the selected object throughout the video, and the tracking results will be displayed in the window.
5. Press the 'Esc' key to exit the script.

### 2. object_tracking_KCF.py

This script uses the KCF algorithm for object tracking.

1. Run the script:
2. A window will open, displaying the video frames.
3. Use the mouse to select the region of interest (ROI) by drawing a bounding box around the object you want to track.
4. The script will track the selected object throughout the video, and the tracking results will be displayed in the window.
5. Press the 'Esc' key to exit the script.

## File Structure

- `object_tracking_CSRT.py`: Python script for object tracking using the CSRT algorithm.
- `object_tracking_KCF.py`: Python script for object tracking using the KCF algorithm.
- `race.mp4`: Sample video file for object tracking (download and place in the repository directory).
- `README.md`: This file.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments

- The OpenCV library and its contributors.
