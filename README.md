## Object Detection using TensorFlow.js and MobileNet
This project demonstrates a simple implementation of object detection in a web application using TensorFlow.js and the MobileNet pre-trained model. The application captures video from the user's device camera and continuously predicts the objects visible in the frame.

### Features
- Real-time object detection in the browser
- Utilizes TensorFlow.js and the MobileNet pre-trained model
- Responsive design for mobile and desktop devices
- No need to install additional software or libraries

### Prerequisites
- A modern web browser with support for WebRTC and TensorFlow.js (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge)

### Usage
- Clone the repository or download the HTML file.
- Open the HTML file in a compatible web browser.
- Grant permission to access your device's camera when prompted.
- Observe the real-time object detection results displayed below the video feed.

### Description
This project contains a single HTML file that uses Bootstrap for styling, jQuery for handling DOM elements, and TensorFlow.js for object detection. The MobileNet pre-trained model is loaded directly from the TensorFlow.js CDN.

The web application captures the video feed from the device's camera and displays it on the screen. A hidden canvas element is used to capture frames from the video feed, and the MobileNet model classifies the objects in these frames. If the detected object has a prediction probability of 0.5 or higher, the result is displayed below the video feed. The object detection process is performed in real-time, continuously updating the predictions as the video feed changes.

### Demo
<img width="236" alt="Screenshot 2023-04-12 at 12 07 27 AM" src="https://user-images.githubusercontent.com/61319491/231348022-e85486bc-76eb-43fc-96d6-3334a51057e2.png">

<img width="210" alt="Screenshot 2023-04-12 at 12 17 40 AM" src="https://user-images.githubusercontent.com/61319491/231348355-1b4cb1bb-8160-474f-8005-8735676c1b85.png">


