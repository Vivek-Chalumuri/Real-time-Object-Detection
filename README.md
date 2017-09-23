# Real-time-Object-Detection
Real time Object Detection with Tensorflow

1. Install Object Detection API https://github.com/tensorflow/models/tree/master/research/object_detection
    
    NOTE: Most important step while installing is to run the following command
      # From models/research/
      protoc object_detection/protos/*.proto --python_out=.
      
2. Replace models/research/object_detection/utils with this utils folder

3. Place obj_detection.py file in models/research/object_detection/


