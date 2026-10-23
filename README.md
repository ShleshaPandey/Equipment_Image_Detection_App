# Equipment Image Recognition App 
## Description
This repository contains code for a computer vision project that utilizes YOLOv8 for equipment detection. The project includes Flask-based APIs for performing object detection on images using YOLOv8 architecture.

## Dataset 
The project uses an annotated image dataset.
The dataset contains 137 images annotated in an object detection format

## Dataset Details:

Images: 137

Annotated Classes: AC, Fan, Generator, Meter, Pump

## Usage details:
Run the Flask app: python app.py

The application provides an object detection endpoint that accepts image uploads through an HTTP POST request.

The endpoint returns detection information and output references according to the API response format.

Consult the application configuration for the exact endpoint URL and request requirements.

## Output
The application can produce annotated images highlighting detected objects.

Detection results may include:

Object category labels

Bounding boxes around detected objects

Confidence scores

References to generated output images


## Example Output:

<img width="570" height="537" alt="image" src="https://github.com/user-attachments/assets/f25e605b-276d-4bb6-9211-5882ec9f63da" />

<img width="625" height="457" alt="image" src="https://github.com/user-attachments/assets/cfa4b501-1df2-43e3-8a03-65dd6d9bc74f" />


In the example above, the green bounding boxes represent detected objects, and the corresponding labels indicate the object classes. The level of confidence for each detection is also displayed.

The API response includes a JSON format with details about the detected objects and the path to the annotated image, providing a comprehensive summary of the object detection results.

## Contributing
Contributions are welcome! Please follow the Contribution Guidelines for more details.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
YOLOv8: https://github.com/ultralytics/yolov8

Roboflow: https://roboflow.com/
## Contact
For questions or inquiries, please contact shlesha.pandey9@gmail.com
