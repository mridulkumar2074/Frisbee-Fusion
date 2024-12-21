# Frisbee Fusion: Game On with Gesture Control  

## Project Overview  
Frisbee Fusion introduces a unique gaming experience by transforming a simple Frisbee into a real-time game controller. Using OpenCV for computer vision, the system captures gestures via a webcam, processes them through color segmentation and contour tracking, and maps them to in-game actions like steering and nitro boosts. This hands-free, intuitive interface enhances gaming immersion and demonstrates the potential of gesture-based systems for human-computer interaction.  

## Features and Technologies  
- **Technologies**: Python, OpenCV, DirectInput (DirectX), NumPy, Imutils.  
- **Core Functionalities**: Gesture recognition through HSV color space conversion, Gaussian blur, and morphological transformations for noise reduction and accurate contour detection.  
- **Performance**: Real-time responsiveness with >90% accuracy and sub-100ms latency, ensuring seamless gameplay.  
- **Customization**: Dynamic HSV calibration using trackbars for adaptable gesture detection across different lighting conditions.  
- **Hardware**: Cost-effective implementation requiring only a standard webcam and PC.  

## Implementation Highlights  
- **Gesture Mapping**: Real-time detection of Frisbee movements to trigger in-game actions such as steering left or right and activating nitro boosts.  
- **Key Simulation**: Custom DirectInput logic to simulate precise keypresses for smooth interaction with games.  
- **Visual Feedback**: On-screen cues and bounding boxes provide real-time gesture recognition updates to users.  

## Challenges Addressed  
- Optimized gesture detection for varied lighting and environments using preprocessing techniques.  
- Improved processing efficiency by focusing on regions of interest and minimizing computational overhead.  
- Developed a robust error-handling mechanism to ensure consistent performance.  

## Future Enhancements  
- Integration of machine learning models for improved and adaptive gesture recognition.  
- Expansion to multi-hand and full-body tracking for more interactive gameplay.  
- Broader application scope, including robotics, virtual reality, and assistive technologies.  

## How to Run  
1. Clone this repository.  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
