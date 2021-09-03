
### Disclaimer

The content of this document is confidential and intended only for individuals participating in interviews by ITXOTIC SDN BHD. Sharing any part of this document with any third party, without a written consent of ITXOTIC SDN BHD is strictly forbidden.

### Challenge Question

Create a web app that displays a real-time video/image stream from a server's backend media. The architecture should be as follows.

![Image of image1](https://github.com/itxotic-dev/ITX_Screening_Test/blob/fullstack-screen/images/image1.png)
Basic visualization of system architecture

  

#### Notes :

1.  The CCTV/webcam is connected directly to the server side and not to the client side. Therefore, no client’s webcam is used for this challenge.
    
2.  The server side will publish a [real-time](https://en.wikipedia.org/wiki/Real-time_computing) stream to its connecting clients.
    
3.  You may use any media transport protocol to fulfill the real-time requirement. Keep in mind that this system should also be able to support multiple CCTV/webcam instances.
    
4.  Multiple clients also should be able to connect to the backend and receive the same stream as other clients.
    
5.  This challenge evaluates knowledge of building and developing both the front-end and back-end sides of the system.
    

#### Criteria of Assessment:

1.  MERN Stack implementation is encouraged.
    
2.  Adequate implementation of HTML, CSS and javascript.
    
3.  Support PWA/ Reactive screen sizes.
    

  

#### Extra Point Assessment:

1.  Good client side styling/ design
    
2.  Organized code base structure with good naming convention.
    
3.  Any additional features that are related but not mentioned in the main task. That can showcase your knowledge in certain criteria. Eg MongoDB.
    
4.  Applying a simple detection on client side using TensorFlow.js. Use the streaming feed broadcasted from the server as its input and show/ visualize its output to be shown to the client. Eg: People detection, face mask or any simple detection that suits your understanding.
    
5.  Support for additional video/image sources such as local on-server video files or Youtube videos.
    
6.  Display of performance measures, such as videos processed per-second and inference speed in frames per second. System wide performance measure such as maximum number of video sources until inference rate drops below a certain value will also add points to the assessment.
    

### Due

This challenge is expected to be completed within 3-6 days from the day participants received this challenge. However, the time of completion is not our prime scoring criteria in this challenge. You may request extension of time to suit your developing time. 
After successfully finishing the challenge, please submit your completed work to info@itxotic.com
