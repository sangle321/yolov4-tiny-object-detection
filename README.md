#Step

- Clone the Darknet git repository
- Create yolov4-tiny and training folders in your google drive
- Create & upload the files we need for training ( i.e. “obj.zip” , “yolov4-tiny-custom.cfg”, “obj.data”, “objnames”  and “process.py” ) to your drive
- Mount drive and link your folder 
- Make changes in the Makefile to enable OPENCV and GPU 
- Run make command to build darknet 
- Copy the files “obj.zip”, “yolov4-tiny-custom.cfg”, “obj.data”, “obj.names”, and “process.py” from the yolov4-tiny folder to the darknet directory in Colab VM
- Run the process.py python script to create the train.txt & test.txt files
- Download the pre-trained YOLOv4-tiny weights
- Train the detector
- Check performance
- Test your custom Object Detector