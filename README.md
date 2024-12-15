Traffic System Management with Arduino and YOLO
This project is focused on building a Traffic System Management solution using Arduino and YOLO (You Only Look Once) for real-time object detection. The system integrates hardware (Arduino and sensors) with a pre-trained YOLO model for detecting vehicles in a traffic system.

Project Structure
The project is organized into the following directories and files:
- ESP32 files: Configuration files and scripts for setting up and using the ESP32 microcontroller for communication with traffic sensors and other peripherals.
- Library: Contains essential libraries for hardware control, sensor data handling, and communication with the microcontroller.
- Pre-trained model: A pre-trained YOLO model used for vehicle detection in the traffic management system.
- Python files: Python scripts that manage the system, including data processing, running the YOLO model, and controlling the traffic system.
- response_log.txt: A log file to record responses and events from the system for debugging and performance monitoring.
- yolov8n.pt: YOLOv8 model file used for vehicle detection and tracking in the traffic system.

Features
- Real-time vehicle detection using the YOLOv8 model.
- Traffic system management using Arduino and ESP32.
- Python-based data processing and communication with the hardware.
- Logging of system events for monitoring and debugging.

Requirements
- Hardware:
  - Arduino (ESP32 board)
  - Camera for vehicle detection
  - Sensors for traffic management
- Software:
  - Python
  - OpenCV
  - YOLOv8 model
  - Arduino IDE and libraries

Installation
1. Clone the repository:
   git clone https://github.com/JehanSadik45353563/Traffic-System-Management-with-Arduino-and-YOLO.git
   cd traffic-system-management
2. Install the required Python libraries:
   pip install -r requirements.txt
3. Set up the Arduino hardware:
   - Connect the Arduino (ESP32) board to your computer and upload the necessary sketches using the Arduino IDE.
4. Run the Python scripts:
   - Use the Python scripts in the Python files directory to manage the traffic system and run the vehicle detection using the YOLO model.

Usage
1. Set up the Arduino and sensors: Follow the configuration in the ESP32 files to get the hardware up and running.
2. Run the Python scripts: Execute the Python scripts to monitor traffic and manage the system.
3. Use the YOLO model: The pre-trained yolov8n.pt model is used for detecting vehicles in real-time.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

- YOLOv8 for object detection.
- Arduino community for their open-source hardware and libraries.
