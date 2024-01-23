# Webcam Image Capture Script

This is a simple Python script for capturing images from a webcam and saving them to a specified directory. The script is designed to collect images for two labels, 'awake' and 'drowsy'.

## Features

- GPU/CPU Selection: The script checks for GPU availability and selects the appropriate device (GPU or CPU).
- Image Storage: Captured images are saved to a specified directory under 'data/images'.
- Label and Image Count: Users can customize the script by providing labels and the number of images to capture.
- Webcam Feed: Real-time webcam feed is displayed while capturing images.
- Termination: The script can be terminated by pressing 'q'.
- Timestamp: Each captured image is named with a timestamp.

## Prerequisites

- Python 3
- PyTorch
- OpenCV

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/AmmarMohamed0/Webcam Image Capture.git
    ```

2. Install dependencies:

    ```bash
    pip install torch opencv-python
    ```

3. Run the script:

    ```bash
    python image_capture_script.py
    ```

## Customization

- **Labels**: Edit the `labels` list in the script to specify your own labels.
- **Number of Images**: Modify the `number_imgs` variable to set the desired number of images for each label.

## Contributing

Contributions are welcome! Feel free to open issues and pull requests.
