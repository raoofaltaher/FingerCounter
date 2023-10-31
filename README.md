# FingerCounter
Real-time Finger Counting Application



his application uses computer vision to detect and count the number of fingers held up in real-time using a webcam. By leveraging the Mediapipe, the application is able to accurately identify hand landmarks and ascertain the status (up or down) of each finger. Key features include:

Hand Detection & Tracking: The application identifies hands within the webcam feed and overlays landmarks on them to show detected positions.

Finger Counting: The application counts the number of fingers held up and displays the count on the screen. For instance, if you hold up three fingers, the number '3' will be prominently displayed.

Visual Feedback: Accompanying the finger count, the application showcases a visual representation corresponding to the number of fingers held up. This is achieved using predefined images for each finger count stored in the 'hands' folder.

Performance Metrics: The application also calculates and displays the frames-per-second (FPS) to give users an idea about its real-time performance.
