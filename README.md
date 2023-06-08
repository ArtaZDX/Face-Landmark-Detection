# Face Landmark Detection using MediaPipe and OpenCV

This project demonstrates the usage of the MediaPipe and OpenCV libraries for face landmark detection in both images and real-time video.
<br />

## Requirements

This project requires the following Python libraries:

- OpenCV
- MediaPipe

```bash
pip install -r requirments.txt
```
<br />

## How it Works
The program works in two parts:

<b>Static Image Processing:</b> The program first reads image files from the IMAGE_FILES list (to be filled by the user) and detects facial landmarks in them. Detected landmarks are then annotated on the images and saved with the prefix 'annotated_image'.

<b>Live Webcam Feed Processing:</b> The program then opens the webcam and continuously detects and displays facial landmarks on the user's face in real-time.

<b>Note: In both parts, the program uses the FaceMesh solution from MediaPipe, with a confidence threshold set to 0.5.</b>
<br />

## Usage

To use this program, simply run it with a Python interpreter after adding the paths of the images you want to process in the IMAGE_FILES list.

When you run the program, it will process the images and then start the webcam feed. To exit the webcam feed, press Esc.
<br />

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
<br />

## License

The code in this project is open-sourced software licensed under the MIT license.
<br />

## Acknowledgements
- MediaPipe
- OpenCV