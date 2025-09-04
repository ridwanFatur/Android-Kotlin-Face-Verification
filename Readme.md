# Face Verification

**Face Verification** is an Android application built with Kotlin that allows users to add face data to a local database and perform real-time face verification using the device camera. This app leverages Jetpack Compose for UI, MediaPipe for face detection and embedding, and Room for local data storage.

![Home Page](Home%20Page.jpeg)
[▶️ Watch Demo](Demo.mp4)

## Features

1. **Add Face Data**  
   - Users follow on-screen instructions to face in different directions (left, right, up, down, forward).  
   - The app captures multiple screenshots to generate embeddings for each direction.  
   - All data is stored locally on the device.

2. **Real-Time Face Verification**  
   - The app verifies the user's face in real-time using the camera.  
   - Detected face embeddings are compared with stored embeddings for verification.

## Technology Used

- **Android Kotlin**  
- **Jetpack Compose** for UI  
- **MediaPipe** for Face Detection and Image Embedding  
- **Room** for Local Database  

## How to Use

1. Install the **APK** on an Android device.  
2. Grant camera permissions when prompted.  
3. Open the app and select **Add Face Data** to register your face.  
4. Follow the instructions to look in different directions while the app captures screenshots.  
5. Once face data is added, you can use **Verify Face** to check identity in real-time.

## Notes

- All face data is stored locally; nothing is uploaded to any server.  
- Ensure good lighting for accurate detection and verification.  

---

Face Verification is a simple yet powerful tool for local face data management and verification on Android devices.
