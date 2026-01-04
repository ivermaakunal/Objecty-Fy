🚀 Real-Time Object Detection Desktop App
A lightweight cross-platform desktop application built with Electron.js and TensorFlow.js that performs real-time object detection using the COCO-SSD model.
This app leverages the user's webcam to identify and label everyday objects (like chairs, cell phones, and laptops) with high accuracy and low latency.

✨ Features
- Real-time Detection: Instantaneous object identification via webcam feed.
- Desktop Native: Built with Electron, allowing it to run as a standalone app on Windows, macOS, and Linux.
- Privacy-Focused: All machine learning processing happens locally on the client side; no data is sent to a server.
- Clean UI: Simple, responsive interface built with HTML5 and CSS3.

🛠️ Tech Stack
> Frontend: HTML5, CSS3, JavaScript
> Framework: Electron.js (Desktop Environment)
> Machine Learning: TensorFlow.js
> Model: COCO-SSD (Common Objects in Context)

📦 Installation & Setup
> Clone the repository
> Install dependencies : npm install or npm i
> Run the application : npm start

🧠 How it Works
The app initializes the COCO-SSD model, which is a "Single Shot MultiBox Detector" designed to track multiple objects in a single image. Once the webcam stream starts, the model scans each frame, draws bounding boxes, and predicts the class of the object with a confidence score.

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
