# Virtual Hand Painter  
A computer vision-based application that allows users to draw digitally using only hand gestures. The project leverages **MediaPipe** for hand tracking and **OpenCV** for real-time video processing.  

## Features  

### Real-time Hand Tracking with Machine Learning  
- Uses **MediaPipe’s deep learning-based hand tracking model** to detect and track hand landmarks in real-time.  
- Identifies key hand positions and maps gestures to drawing actions with high accuracy.  

### Multiple Drawing Modes  
- **Freehand Drawing:** Move your **index finger** to draw continuous strokes.  
- **Rectangle Mode:** Draw precise rectangles using hand gestures.  
- **Circle Mode:** Create circles by defining center and radius with hand movements.  
- **Straight Line Mode:** Draw straight lines between two tracked points.  

### Gesture-based Full Canvas Clear  
- A specific **hand gesture** clears the entire drawing canvas instantly.  

### Screenshot and Save Feature  
- Capture your artwork and save it as an image file for future reference.  

### Machine Learning-powered Efficiency  
- **Lightweight deep learning model** enables fast hand tracking without requiring a dedicated GPU.  
- **Computer vision algorithms** optimize gesture recognition and stroke rendering.  
- **Highly responsive drawing system** ensures minimal lag between gesture recognition and visual output.  

## Technologies Used  
- **Python** – Core programming language  
- **OpenCV** – For computer vision processing  
- **MediaPipe** – Deep learning-based hand tracking  

## Installation  

### Prerequisites  
Ensure you have **Python 3.7+** installed. You can check your version using:  
```bash
python --version
