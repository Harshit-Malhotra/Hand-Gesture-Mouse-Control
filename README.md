# Hand Gesture Mouse Control

This project allows you to control your computer's mouse using hand gestures detected through your webcam. The project leverages OpenCV for video capture, MediaPipe for hand detection, and PyAutoGUI for controlling the mouse cursor.

## Features

- **Hand Detection:** The project uses MediaPipe to detect hands and their landmarks.
- **Mouse Movement:** You can control the mouse cursor by moving your index finger.
- **Clicking:** You can simulate a mouse click by bringing your thumb close to your index finger.

## How It Works

1. The webcam captures live video feed.
2. MediaPipe processes the video to detect hand landmarks.
3. The index finger's position is tracked to move the mouse cursor.
4. A mouse click is simulated when the thumb comes close to the index finger.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your system.
- A working webcam.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/hand-gesture-mouse-control.git
    ```
2. Navigate to the project directory:
    ```bash
    cd hand-gesture-mouse-control
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the script:
    ```bash
    python hand_mouse_control.py
    ```
2. A window will open showing the webcam feed with hand detection. Use your index finger to move the cursor, and bring your thumb close to your index finger to simulate a click.

3. Press the 'q' key to exit the program.

## Troubleshooting

- **Cursor is not moving:** Ensure that the webcam is working and that your hand is clearly visible in the frame.
- **Click not registering:** Make sure your thumb is close enough to the index finger, and there is enough light for the camera to detect the hand gestures.

## License

This project is open-source and available under the MIT License.
