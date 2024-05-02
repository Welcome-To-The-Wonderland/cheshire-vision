# cheshire-vision

- Develop a system that can detect and track multiple objects in real-time from video feeds, useful
  for applications such as surveillance, traffic monitoring, or advanced driver-assistance systems (ADAS)

Image Acquisition and Pre-processing (C++)
Purpose: Capture video frames and perform initial processing like resizing, normalization, and color correction.
Tools: Use OpenCV in C++ for capturing video streams and initial image manipulations. This takes advantage of C++'s speed in handling intensive image processing tasks.

Deep Learning Model for Object Detection (Python)
Purpose: Detect objects in each frame.
Tools: Use Python with TensorFlow or PyTorch. These libraries are rich in pre-trained models like YOLO, SSD, or Faster-RCNN, which can be easily integrated and are highly effective for object detection tasks.

Tracking Algorithm (C++)
Purpose: Track the movement of detected objects across frames to maintain their identities.
Tools: Implement tracking algorithms like SORT (Simple Online and Realtime Tracking) or more advanced ones like DeepSORT in C++. These algorithms benefit from C++'s efficiency in processing video frames in real time.

Data Handling and Integration (Python)
Purpose: Handle the integration of C++ and Python components, manage data flow, and possibly interface with databases or web services for storing or further processing.
Tools: Use Python’s libraries like NumPy for data manipulation and Pybind11 or Boost.Python for calling C++ code from Python.

User Interface (Python/C++)
Purpose: Display the tracked objects and their trajectories in real time.
Tools: You can use PyQt or Tkinter in Python for a simple interface or create a more performance-oriented GUI in C++ with Qt or similar frameworks.
