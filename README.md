# Let's Talk

## Overview
Let's Talk is an innovative mobile application developed to facilitate communication between hearing individuals and the deaf and mute community. The app features a range of functionalities including Text-to-Sign translation, Sign-to-Text conversion, Voice-to-Sign translation, and real-time object detection to bridge the communication gap.

## Features
- **Text-to-Sign Translation:** Converts written text into sign language.
- **Sign-to-Text Conversion:** Translates sign language into written text.
- **Voice-to-Sign Translation:** Transforms spoken language into sign language.
- **Real-time Object Detection:** Identifies objects in real-time and labels them.

## Technologies Used
- **Firebase ML Vision (v20.0.1):** Used for image labeling and machine learning capabilities.
- **Yarolegovich Sliding Nav (v1.1.1):** Integrated for an enhanced user navigation experience.

## Installation
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/lets-talk.git
    cd lets-talk
    ```

2. **Open in Android Studio:**
   - Launch Android Studio.
   - Open the cloned project directory.

3. **Dependencies:**
   - The project uses Gradle for dependency management. Ensure the following dependencies are included in your `build.gradle` file:

     ```gradle
     dependencies {
         implementation 'com.google.firebase:firebase-ml-vision:20.0.1'
         implementation 'com.yarolegovich:sliding-root-nav:1.1.1'
         // Add other dependencies here
     }
     ```

4. **Firebase Configuration:**
   - Set up a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
   - Download the `google-services.json` file from the Firebase Console and place it in the `app` directory of your Android Studio project.

5. **Build and Run:**
   - Sync your project with Gradle files.
   - Build and run the application on an Android device or emulator.

## Usage
1. **Text-to-Sign Translation:**
   - Enter text in the provided field and press the "Translate" button to see the sign language equivalent.

2. **Sign-to-Text Conversion:**
   - Use the camera to capture sign language gestures. The app will convert these gestures into text.

3. **Voice-to-Sign Translation:**
   - Speak into the device's microphone. The app will convert your speech into sign language.

4. **Real-time Object Detection:**
   - Point your device's camera at objects. The app will label and display the names of the detected objects.



## Acknowledgments
- [Firebase ML Vision](https://firebase.google.com/docs/ml-kit/vision) for providing machine learning capabilities.
- [Yarolegovich Sliding Nav](https://github.com/yarolegovich/SlidingRootNav) for the sliding navigation drawer library.

