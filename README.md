# Hand2CursorTech

**Hand2CursorTech** is a vision-based system for controlling your computer cursor using hand gestures. This project utilizes Python libraries like OpenCV, Mediapipe, and PyAutoGUI to achieve real-time hand detection, gesture recognition, and cursor actions.

## Features

- **Cursor Movement:** Navigate the cursor on the screen using hand gestures.
- **Click Functions:** Perform left, right, and double clicks with specific hand gestures.

## Requirements

- Python 3.x
- OpenCV: `pip install opencv-python`
- Mediapipe: `pip install mediapipe`
- PyAutoGUI: `pip install pyautogui`
- Webcam

## How It Works

1. **Capture Video:** Utilizes your webcam to capture video frames.
2. **Hand Detection:** Mediapipe’s hand detection model identifies your hand in the frames.
3. **Landmark Extraction:** Extracts key points on your hand (landmarks) for gesture recognition.
4. **Gesture Recognition:** Analyzes hand landmarks to determine gestures (e.g., V-shape for cursor movement, extended middle finger for left click).
5. **Cursor Control:** Automates cursor movement or clicks based on recognized gestures using PyAutoGUI.

## Customization

This project is highly customizable. You can:

- Add new gestures for additional functionalities (e.g., scrolling, dragging).
- Refine gesture recognition logic for improved accuracy.
- Incorporate error handling and user feedback mechanisms.

Feel free to experiment and contribute to its evolution!

## Disclaimer

This project is intended for educational purposes. The accuracy and performance of the gesture recognition system may vary depending on environmental factors (e.g., lighting, background) and individual hand postures.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## ✉️ Contact
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lalit-swami/)](https://www.linkedin.com/in/lalit-swami/) [![Gmail Badge](https://img.shields.io/badge/-Gmail-c14438?style=flat&logo=Gmail&logoColor=white&link=mailto:swamilalit2014@gmail.com)](mailto:swamilalit2014@gmail.com)