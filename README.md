# Object-Detection
OpenCV provides convenient functions that support object detection by allowing the use of various pre-trained models through their weight and configuration files. It can extract and return both the confidence levels and the coordinates of bounding boxes for detected objects. This is particularly useful because OpenCV includes simple functions to draw bounding boxes and label the detected objects with minimal, clean code. Additionally, OpenCV features a built-in method for applying Non-Maximum Suppression (NMS), which helps eliminate redundant detections by keeping only the bounding box with the highest confidence for each object.
![image alt](https://github.com/DivyanshuGupta8103/Object-Detection/blob/ce4f89333dbb72c6b7f3a61d0c1094df1d810775/output.png)

How to set up and run project.

1. Clone the Repository on Another Device

On the new device, open a terminal and run:

git clone(https://github.com/sanskritig741/Object_detection)


---

2. Set Up a Virtual Environment (Optional but Recommended):

 python -m venv venv
source venv/bin/activate       
 On Windows: venv\Scripts\activate


---

3. Install Dependencies:

Make sure you have Python and pip installed. Then install the dependencies:

pip install -r requirements.txt

If you don’t have a requirements.txt, manually install:
pip install opencv-python numpy

(Include other libraries , like opencv , matplotlib, imutils.)


---

4. Run the Project:

Use the command:  object_detection.ipynb

---


5. Extra Notes:
6. project uses a webcam, make sure the  device has webcam .

If you're using pretrained models like YOLO or SSD, ensure they are included or downloaded at runtime.


dependencies or configurations are attached above 

