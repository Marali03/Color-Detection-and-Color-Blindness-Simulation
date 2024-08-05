# Color Detection and Color Blindness Simulation

## Description

This project demonstrates real-time color detection and color blindness simulation using a webcam. It performs two main tasks:

1. **Color Detection**: Identifies and extracts the most prominent colors from the webcam feed using the K-means clustering algorithm.
2. **Color Blindness Simulation**: Simulates how individuals with different types of color blindness perceive colors in the webcam feed. Supported simulations include protanopia, deuteranopia, and tritanopia.

## Features

- **Real-time Webcam Feed**: Captures video frames from the webcam.
- **Color Detection**:
  - Converts images from BGR to RGB color space.
  - Uses K-means clustering to identify prominent colors.
  - Displays detected colors as a color palette.
- **Color Blindness Simulation**:
  - Applies transformation matrices for different types of color blindness.
  - Provides a visual comparison of the original and simulated views.
- **Display**:
  - Shows the original webcam feed and the simulated color blindness view in separate windows.
  - Displays detected colors in a color palette plot.

## Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/Marali03/Color-Detection-and-Color-Blindness-Simulation.git
    ```

2. **Navigate to the Project Directory**:

    ```bash
    cd your-repository
    ```

3. **Install Dependencies**:

    Ensure you have the required libraries installed:

    ```bash
    pip install opencv-python numpy scikit-learn matplotlib
    ```

## Usage

1. **Run the Application**:

    Execute the script to start capturing video from the webcam and perform color detection and simulation:

    ```bash
    python color_detection_blindness_simulation.py
    ```

2. **Provide Input**:

    The script captures frames from the webcam automatically, detects colors, and simulates color blindness based on the predefined type ('protanopia').

3. **View Results**:

    - The original webcam feed and simulated color blindness view will be displayed in separate windows.
    - Detected colors will be shown as a color palette.

## Project Structure

- **`color_detection_blindness_simulation.py`**: Main script for capturing video, detecting colors, simulating color blindness, and displaying results.
- **`README.md`**: Documentation file providing an overview and instructions for the project.


## Contributing

Feel free to explore, contribute, or adapt the code to fit your needs. If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
