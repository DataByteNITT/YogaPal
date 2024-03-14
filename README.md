# Yoga-Pal

This application is designed to assist yoga practitioners in improving their poses by providing real-time feedback, tracking progress over time, and offering personalized guidance. Leveraging computer vision techniques, pose estimation models, and interactive user interfaces, it aims to enhance the yoga experience and promote better alignment and form.

## Features

### Pose Estimation
- Integration of pose estimation models like OpenPose and MediaPipe for accurate detection of body joints and key points during yoga poses.
- Real-time analysis of the user's pose by comparing it with a reference video or ideal pose.

### Angle and Euclidean Distance Calculation
- Calculate joint angles and distances for pose accuracy assessment.

### Feedback Generation
- Generate text or voice feedback based on joint differences using Text-to-Speech libraries.

### User Interface
- Interactive app for smartphones with an intuitive user interface with a beginner's guide for yoga poses.
- Real-time textual and voice-guided corrections to help users perfect their poses.

### Progress Tracking
- Feature to track the user's progress over time, allowing them to see improvements in flexibility and strength as they continue their yoga practice.

## Tech Stack
- **Computer Vision Models:** MediaPipe for pose estimation
  - MediaPipe is a framework developed by Google that offers tools and solutions for building complex multimedia pipelines, particularly focusing on computer vision and machine learning applications.
- **Mobile App Development:** Flutter, TensorFlow Lite
  - Flutter is an open-source UI software development kit created by Google, used to develop cross-platform applications from a single codebase.
  - TensorFlow Lite provides tools that enable on-device machine learning, allowing developers to run their trained models on mobile, embedded, and IoT devices.
- **Programming Languages:** Python & TensorFlow framework
  - TensorFlow is a free and open-source software library for machine learning and artificial intelligence, developed by the Google Brain team.
