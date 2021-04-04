Welcome to the ITXOTIC AI Training and Inferencing Challenge.
 The challenge has two tasks to be completed in order to proceed to the next stage. 
 You have **5 days** to complete this task, starting from the day the test email is sent. You must submit before midnight of the 5th day.

 1. Deep Learning model training with https://gitlab.com/azolkipli/ITXOTIC_Screening_Test dataset
    - The candidate is required to train an Object Detection AI model with the dataset in this gitlab repository
    
    - You may choose any model that you prefer. But, it must be able to do realtime detection, with fairly high accuracy on CPU (not GPU)
    
    - The dataset is a set of annotated pothole images. 
        - The dataset is written in Yolo Darknet .txt format.
        - The .txt file consists of class, x_center, y_center, width, and height for each row. 
        - All the informations are normalised between 0-1 except for the class. 
        - To convert the normalized x_center and y_center into a pixels format, simply multiply it with the width(x_center) or height(y_center) of the image. 
        - Same goes to the normalized width and height. The class numbers are zero-indexed (start from 0).
        - There are 1564 images with 720x480 in size. There are 3530 annotated potholes inside this dataset.


    - Choose any framework you are comfortable with (Keras, Tensorflow, Pytorch, Caffe, etc)

    - The generated model and the detection script must then be submitted to itxotic@gmail.com with the subject

        - _<firstname,lastname> - Pothole Detection <Framework-Model name>_
        - eg, **Anuar Ibrahim - Pothole Detection Pytorch-MobilnetV2-SSD**

    - Share details of the AI model and training decisions* What examples details to share
        - choice of model (yolo, vgg16, mobilenet, etc)
        - choice of framework (pytorch, tensorflow, keras, etc)
        - data augmentation decisions (if any)
        - train/test/validate ratio
        - accuracy & latency (ms) average
        - anything else of note
    - The AI model will be tested with our sample data to validate it is working and has acceptable level of speed and accuracy.
    

2. Installation & Inferencing demonstration using on OpenVINO toolkit
    - The candidate is required to demonstrate the ability to successfully install OpenVINO on your desktop or inferencing device

    - The candidate is then required to find a readily avaialable video analytics project that can be demonstrated during the interview.
        - Refer to _https://github.com/intel-iot-devkit_ for some examples.

    - If available, the candidate should demonstrate the ability to switch inferencing on devices (VPU, CPU, GPU, FPGA).


3. _Optional: Convert pothole training model into Openvino IR model & demonstrate_

If you have any questions during doing the task, please email itxotic@gmail.com
