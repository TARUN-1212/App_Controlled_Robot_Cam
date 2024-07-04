# App_Controlled_Robot_Cam
App-Controlled Robot Car with Live Video Streaming


This repository contains the code and resources for a robot car project controlled through a mobile application and featuring live video streaming from the robot's camera!

**Key Functionalities:**

* **Remote Control:** Control the robot car using a pre-existing mobile app.
* **Live Video Streaming:** View a live video feed from the robot's camera mounted on a mobile device running an IP Webcam app.
* **Open-source Design:** Explore and customize the robot car's functionalities (Arduino code) and user experience (mobile app settings).  (Consider adding a note if your code is licensed under a specific license)

**Hardware Components:**

* **Microcontroller:** Arduino Uno
* **Motor Control:** L293D Motor Control Shield
* **Communication:** HC-05 Bluetooth Module (for robot car control, optional for video streaming depending on the IP Webcam app)
* **Camera:** Mobile Camera (mounted on the robot car, running an IP Webcam app)
* **Power:**
    * 18650 Battery Holder (2 Cell)
    * 2x 18650 Battery Cells (3.7V)
    * On/Off Switch
* **Other:** Jumper Wires, Phone Mount

**Software:**

* **Mobile App:** Download and install an IP Webcam app (e.g., "IP Webcam" or "DroidCam Webcam") on the mobile device mounted on the robot car.

**Getting Started**

This repository provides the following resources:

* **Arduino Code:** The code for controlling the robot car's movement (might require adjustments for video streaming communication).
* **Robot Car Hardware Schematics:** Learn about the robot car's components and assembly process through schematics and diagrams.
* **IP Webcam App Instructions:**  Provide a link or instructions for downloading and setting up the IP Webcam app on the mobile device.

**Building Instructions**

1. **Review the Hardware Schematics:** Familiarize yourself with the components listed above and their connections. (Consider adding a link to the schematics in this section)
2. **Assemble the Robot Car:** Follow the provided schematics and wiring diagrams to assemble the robot car, including the motor control shield, mobile device mount, and Bluetooth module connection (if applicable).
3. **Set up the IP Webcam App:**  Download and install the chosen IP Webcam app on the mobile device. Configure the app settings for video resolution, frame rate, and  (if applicable) access credentials. Refer to the app's documentation for specific instructions.
4. **Connect the Robot Car and Mobile App (Optional):**  If the IP Webcam app uses Bluetooth for video transmission, establish a connection between the robot car's Bluetooth module and the mobile device. Otherwise, the connection might be established through Wi-Fi depending on the app. Refer to the app's documentation for specific instructions.
5. **Update the Arduino Code (Optional):** Depending on the IP Webcam app's video streaming functionality, you might need to modify the Arduino code to establish a connection with the mobile device's IP address and receive the video stream.

**Further Exploration**

This project serves as a foundation for further development. You can explore features like:

*  Integrating different communication protocols (e.g., Wi-Fi) for robot car control or video streaming (depending on the IP Webcam app).
*  Implementing video processing algorithms on the robot car (using Arduino) or within the IP Webcam app (if supported).
*  Enhancing the mobile app experience by finding a suitable pre-built app with features like on-screen controls or video display customization.

**Community**

We welcome contributions and improvements to this open-source project! Feel free to share ideas, bug fixes, or new functionalities through pull requests.

**License**

(If your code has a specific license)

This project is licensed under the [License Name](link to license).

**Note:**

* Replace the bracketed placeholders with specific details about your project, such as a link to the schematics (if available) and the specific IP Webcam app you recommend.
* Consider mentioning any specific libraries used in the Arduino code for the robot car (if applicable).
* Feel free to add screenshots or images of your robot car to enhance the README file.

