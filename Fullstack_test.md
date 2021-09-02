Disclaimer
The content of this document is confidential and intended only for individuals participating in interviews by ITXOTIC SDN BHD. Sharing any part of this document with any third party, without a written consent of ITXOTIC SDN BHD is strictly forbidden.
Challenge Question
Create a web app that displays a real-time video/image stream from a server's backend media. The architecture should be as follows.

Basic visualization of system architecture

Notes :
The CCTV/webcam is connected directly to the server side and not to the client side. Therefore, no client’s webcam is used for this challenge.
The server side will publish a real-time stream to its connecting clients.
You may use any media transport protocol to fulfill the real-time requirement. Keep in mind that this system should also be able to support multiple CCTV/webcam instances.
Multiple clients also should be able to connect to the backend and receive the same stream as other clients.
This challenge evaluates knowledge of building and developing both the front-end and back-end sides of the system.

Criteria of Assessment:
MERN Stack implementation is encouraged.
Adequate implementation of HTML, CSS and javascript.
Support PWA/ Reactive screen sizes.

Extra Point Assessment:
Good client side styling/ design
Organized code base structure with good naming convention.
Any additional features that are related but not mentioned in the main task. That can showcase your knowledge in certain criteria. Eg MongoDB.
Applying a simple detection on client side using TensorFlow.js. Use the streaming feed broadcasted from the server as its input and show/ visualize its output to be shown to the client. Eg: People detection, face mask or any simple detection that suits your understanding.
Support for additional video/image sources such as local on-server video files or Youtube videos. 
Display of performance measures, such as videos processed per-second and inference speed in frames per second. System wide performance measure such as maximum number of video sources until inference rate drops below a certain value will also add points to the assessment. 
Due
This challenge is expected to be completed within 3-6 days from the day participants received this challenge. However, the time of completion is not our prime scoring criteria in this challenge. You may request extension of time to suit your developing time.
