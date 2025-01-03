# Hololens-AR：situated visualization with OWL-ViT

The project implements an AR interactive system integrated with camera image capture and user voice input on the Microsoft HoloLens 2 device. The system utilizes a deep learning service built with Flask and PyTorch, employing a zero-shot detection model based on Vision Transformer (OWL-ViT) for image detection, with inference accelerated via ONNX. After matching the detection results with the user's voice input, the corresponding objects are mapped into the AR scene, supporting downstream tasks such as counting, sorting, allocation, and layout. The program is developed in the Unity environment, achieving the mapping from 2D image space to AR 3D space and providing interactive functionality within the AR scene.
## zero-shot detection
![zreo shot detection](image/detection.png "zreo shot detection")
## counting
![counting](image/vertical-counting.png "counting")
![counting](image/horizontal-counting.png "counting")
## sorting(size)
![sorting](image/sorting.png "sorting")
## allocation/assignment
![assignment](image/assignment1.png "assignment")
![assignment](image/assignment23.png "assignment")
## layout
![layout](image/layout.png "layout")
## Contact me for source code
fuxinghui7@gmail.com

