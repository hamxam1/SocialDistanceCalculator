# SocialDistanceCalculator
   Tool to monitor social distancing from CCTV, videos using Python, Deep learning, Computer Vision. This tool can 
   automatically estimate interpersonal distance from uncalibrated RGB cameras. Can be used at public places and workplace.

   This tool has following features:

   * Detect humans in the frame with yolov3.
   * Calculates the distance between every human who is detected in the frame.
   * Shows how many people are at High, Low and Not at risk.
   
   
## Requirements:

    You will need the following to run this code:
    Python 3.5.2
    Opencv(CV2) 4.2.0
    numpy 1.14.5
    argparse
    
     Yolo3 weights can be downloaded from 
    here : https://pjreddie.com/media/files/yolov3.weights)
    
    For running: 
    Good GPU, for faster results. CPU is also fine(I have tried it on CPU).
    

   

## References:

   Yolov3 object detection : https://www.learnopencv.com/deep-learning-based-object-detection-using-yolov3-with-opencv-python-c/
   Prespective Transform : https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_geometric_transformations/py_geometric_transformations.html

\
