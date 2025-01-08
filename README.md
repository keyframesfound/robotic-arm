
# Installation Guide for Robotic Arm Project

## Prerequisites
- Python (recommended latest stable version)
- Git (for cloning the repository)

## Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/keyframesfound/robotic-arm.git
   cd robotic-arm
   ```

2. **Set Up Python Environment**
   It's recommended to create a virtual environment:
   ```bash
   python -m venv venv
   ```

3. **Activate Virtual Environment**
   - On Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Run the Project**
   ```bash
   python main.py
   ```
## GPIO Connections
Raspberry Pi       PCA9685
---------------------------
GPIO 2 (SDA)   -> SDA
GPIO 3 (SCL)   -> SCL
3.3V or 5V     -> VCC
GND            -> GND

Servo Motor Connections:
---------------------------
Servo Signal   -> PCA9685 PWM Channels (0 to 4)
Servo Power    -> PCA9685 V+
Servo Ground   -> PCA9685 GND

## License
This project is licensed under the MIT License. See the LICENSE file in the repository for full details.

## Additional Notes
- The repository is currently in development with minimal content
- Make sure you have appropriate permissions if you plan to modify and redistribute the code
- For issues or contributions, you can fork the repository