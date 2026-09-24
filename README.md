## Gayatri Ravada
Computer Vision and Deep Learning for Robotics- real-time perception on the device.
M.S. Computer Science

My graduate research involved implementing a published method from the paper, extending it, and writing it up. Before that, I built a real-time object detection system with spoken feedback for people with low vision, deployed on-device so it worked without a network — where the constraint was end-to-end latency rather than detection accuracy, because a description that arrives late describes something the user has already walked past.

Currently moving toward robotics and physical AI: learned perception on embedded hardware and low-latency sensing.

Research interests — real-time and energy-efficient perception, deep metric and representation learning, event-based and neuromorphic vision, perception for robotic and assistive systems.

Tools:
.  Deep learning
.  PyTorch, TensorFlow, CNN backbones (ResNet / IR-50), loss function design, deep metric learning; Perception 
·  OpenCV, YOLO, RetinaFace, real-time object detection, face recognition, image pipelines; Deployment  
·  On-device and embedded inference, latency profiling, Android Studio 
·  Python, C++, Java, SQL, scikit-learn, Linux, Git

Selected work
[ArcFace with sub-centers and hashed embeddings](https://github.com/Gayatri187/arcface-privacy-preserving-face-recognition) Implemented ArcFace from the paper in PyTorch on an IR-50 backbone with RetinaFace alignment. Extended it with sub-center ArcFace for robustness to label noise, and added a SHA-256 hash layer so verification runs over hashed embeddings rather than raw ones. Written up as a full research report — formulation, geometric interpretation, related work, experimental design.

[Solar energy forecasting: from weather data to sky images](https://github.com/Gayatri187/solar-energy-forecasting) Rebuilt my undergraduate project as a research-style study on Stanford's SKIPP'D dataset. Cleaned three years of minute-level PV data, then forecast one hour ahead with Random Forest and Gradient Boosting, 12% better than smart persistence. Added calibrated uncertainty with conformalized quantile regression, whose 90% ranges hold their coverage even on cloudy days. Finally, trained a PyTorch CNN on sky-camera images for 15-minute forecasting, which beats the same model without images (skill 0.19 vs 0.12). Along the way I found and corrected a one-hour daylight-saving timestamp error in the published image data, using solar geometry.

📫 Connect: 
LinkedIn: https://www.linkedin.com/in/gayatriravada/
Email: gayatriravada187@gmail.com




