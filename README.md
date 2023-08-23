#SecureKDC - Secure Keylogger, Clipboard, and Device Detection
SecureKDC is a Java application that monitors and detects various activities related to keylogging, clipboard manipulation, and external device connection. It offers functionalities to detect and notify about potential security breaches.

Table of Contents
Features
Key Components
Installation
Usage
Configuration
Dependencies
License
Features
Keylogger Detection: Detects potentially suspicious keystrokes, including predefined words, and notifies the user.
Clipboard Monitoring: Monitors clipboard activities, such as copy-paste actions, and alerts if sensitive content is copied.
External Device Detection: Detects the connection and disconnection of external devices like USB drives and sends alerts.
Email Notifications: Sends email notifications to a specified address whenever suspicious activities are detected.
Key Components
The project consists of the following Java classes:

CopyPasteDetector: Monitors clipboard activities and detects copy-paste actions, alerting if certain conditions are met.
DeviceDetect: Detects the connection and disconnection of external devices and sends email alerts.
KeyLogger: Monitors keystrokes, detects predefined keywords, and sends alerts when suspicious words are typed.
SecureKDC: The main class that sets up the system tray and initiates the monitoring components.
Installation
Clone the repository to your local machine.
Ensure you have Java JDK installed.
Set up your Gmail account credentials in the GmailSender class for email notifications.
Usage
Compile the Java files using a Java compiler (e.g., javac).
Run the SecureKDC class to initiate the system tray and start monitoring.
Note: This application is meant for educational and awareness purposes. Ensure you comply with ethical considerations and legal regulations when using it.

Configuration
GmailSender: Configure your Gmail account credentials (email and password) in the sendEmil method for email notifications.
Dependencies
This project uses the following external libraries:

JNativeHook: For global keyboard event listening.
Make sure to include these libraries in your project's classpath.

License
This project is licensed under the MIT License.

