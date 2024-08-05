# Color-Detection-and-Color-Blindness-Simulation
Color Detection and Color Blindness Simulation Using Webcam
Description
This project demonstrates real-time color detection and color blindness simulation using a webcam. The application performs the following tasks:

Color Detection: Identifies and extracts the most prominent colors from the webcam feed using the K-means clustering algorithm.
Color Blindness Simulation: Simulates how individuals with different types of color blindness perceive colors in the webcam feed. It supports simulations for protanopia, deuteranopia, and tritanopia.
Features
Real-time Webcam Feed: Captures video frames from the webcam.
Color Detection:
Converts the image from BGR to RGB color space.
Uses K-means clustering to identify prominent colors.
Displays the detected colors as a color palette.
Color Blindness Simulation:
Transforms the image based on pre-defined matrices for color blindness types.
Provides a visual comparison of the original and simulated views.
Display:
Shows the original webcam feed and simulated color blindness view in separate windows.
Displays detected colors in a separate plot.
How to Use
Clone the Repository:

bash
git clone https://github.com/your-username/your-repository.git
Install Dependencies:
Ensure you have the required libraries installed:

bash
Copy code
pip install opencv-python numpy scikit-learn matplotlib
Run the Application:
Execute the script to start capturing video from the webcam and perform color detection and simulation:

bash
python color_detection_blindness_simulation.py
Provide Input:
The script automatically captures frames from the webcam. It will detect colors and simulate color blindness based on the predefined type ('protanopia').

View Results:

The original webcam feed and simulated color blindness view will be displayed in separate windows.
Detected colors will be shown as a color palette.
Project Structure
color_detection_blindness_simulation.py: Main script for capturing video, detecting colors, simulating color blindness, and displaying results.
README.md: Documentation file providing an overview and instructions for the project.
Future Enhancements
User Interface: Develop a graphical user interface (GUI) for selecting color blindness types and visualizing results more interactively.
Additional Color Blindness Types: Include more types of color blindness and refine simulation accuracy.
Web Application: Implement the functionality as a web-based application for broader accessibility.
Feel free to explore, contribute, or adapt the code to fit your needs. If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.
