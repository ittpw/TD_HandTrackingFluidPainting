# Fluid Painting with Hand Tracking
This repository contains a sample project demonstrating fluid painting using hand tracking.

![sample](https://github.com/ittpw/TD_HandTrackingFluidPainting/assets/20105841/1f644204-9b52-4ed7-9694-8fd7baec6d04)



## Prerequisites
* TouchDesigner Version: 2023.11340
* Operating System: This sample has been tested on MacOS (M1) only (It probably works on Windows too).


## Features
* **Hand Tracking**: Utilizes hand tracking technology to control the painting process.
  * **The tracking focuses on the tip of index finger**, and it can recognize either the left or right hand, although it follows only one at a time.
  * This project uses [MediaPipe](https://github.com/torinmb/mediapipe-touchdesigner) integrated with TouchDesigner for hand tracking.

## Getting Started
1. Clone this repository to your local machine.
2. Open the .toe file with TouchDesigner.
3. Ensure your web camera is connected and permitted to be used by the application.
4. Start interacting using your index finger to paint on the virtual canvas.
5. To clear the painting and start over, press the '1' key on your keyboard at any time during the use of the application.

