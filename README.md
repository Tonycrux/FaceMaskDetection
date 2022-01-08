## Facemask Detection System using Tensorflow Object Detection API
This project was created by Oluyele Sunday Anthony 

Note: The main detection script is the [new_webcam.py](https://github.com/Tonycrux/FaceMaskDetection/blob/master/new_webcam.py) file.
The Detection System will not work if proper installation is not done.

# How to make the Object Detection Feature work
* **Clone this Repository**
  * You just have to clone the repository so you can have access to it in your local machine

* **Make sure python is installed in your local machine**

* **Install conda functionality and don't forget to add to path(Windows)**

* **Visit [this link](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html) to install the Tensorflow Object Detection API**

  * Note: When you get to the part that states "**TensorFlow Object Detection API Installation**" Navigate to the models directory at [/Tensorflow/models](https://github.com/Tonycrux/FaceMaskDetection/tree/master/Tensorflow/models) to clone the repository to place the tensorflow folder.

* **Ensure the `python -m pip install --use-feature=2020-resolver .` run successfully** and 
    You can use the `python object_detection/builders/model_builder_tf2_test.py` to test if your installation was complete in the models/research directory.

* **If your intallation was succefully and the test script run successfully you can now run the new_webcam.py script for the FaceMask Detection System to work**
  * Make sure you have activated your Conda virtual environment using `conda activate tensorflow` then run the detection script using
  `python new_webcam.py`

  You should start getting detections from the GUI application launched.


