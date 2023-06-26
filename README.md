# Real-time Human Pose Estimation in your browser

# A Posenet demo built using ml5.js 

With PoseNet running on TensorFlow.js anyone with a decent webcam-equipped desktop or phone can experience this technology right from within a web browser.

Posenet is a real-time pose detection technique with which you can detect human beings' poses in an Image or in a Video. It uses a Convolution Neural Network (CNN) model to regress pose from a single RGB image. 

# Is it even useful?

Well, Snapchat uses these modules for its users to detect postures. 

Also in Simulator video games like tennis, they use Posenet to detect your body movements and then check if the shot you have taken is correct or not.

# So what is pose estimation?

Pose estimation refers to computer vision techniques that detect human figures in images and videos so that one could determine where someone’s elbow shows up in an image or video. Pose Estimation techniques have many applications such as Gesture Control, Action Recognition and also in the field of augmented reality.


![](https://github.com/Ashutosh9110/posenet_ml5js/blob/main/1.gif) 

# How does it work?

You feed an image to the neural Network that has been trained beforehand on Mobile Network and it provides you with 2 things: whether the 
image has a skeleton or a person is there or not and for this, a confidence score gets generated and once it is generated, it starts searching
for the 17 key points and it assigns every key a confidence score.

# Library used:

ML5.js:  ML5.js is based on TensorFlow. It provides immediate access in the browser to pre-trained models for detecting human poses, generating text, styling an image with another, composing music, pitch detection, common English language word relationships, and much more.

P5.js: p5.js is a JavaScript library for creative coding, with a focus on making coding accessible and inclusive for artists, designers, educators, beginners! p5.js is free and open-source software

# Demo Link: 

Click on the below link either from your cell phone, laptop or desktop with a webcam. Stand in front of the camera at a distance of at least 2 - 3 meters and you will be able to see that the camera is capturing your body movements.

https://ashutosh9110.github.io/Real-time-Human-Pose-Estimation-in-your-browser/
