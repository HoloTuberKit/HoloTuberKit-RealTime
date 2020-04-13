# HoloTuberKit WebRTC for AzureKinect
Simple Volumetric Video capture &amp; AR visualizer for Azure Kinect. 
The capture app is compatible with Windows 10 and the viewer is compatible with Android (ARCore/Vuforia).
<br><br>
[YouTube Video]<br>
[![](https://img.youtube.com/vi/m_uFsbNz-Ko/0.jpg)](https://www.youtube.com/watch?v=m_uFsbNz-Ko)
<br><br>
You can try also YouTube Live version from below.<br>
https://github.com/TakashiYoshinaga/HoloTuberKit-for-AzureKinect
<br><br>
# Requirements
## Azure Kinect Sensor SDK v1.4.0
https://github.com/microsoft/Azure-Kinect-Sensor-SDK/blob/develop/docs/usage.md
<br><br>

## UnityCam
https://github.com/mrayy/UnityCam
<br>
<b>Instalation</b><br>
1) Access folder "RunMe First" -> "x64". <br>
2) Right click on "Register.bat".<br>
3) Click "Run as Administrator" to register UnityCam plugin in Windows. <br>
<br><br>

# How To Use
## Hologram Capture (PC side)
This application captures RGB and Depth image from Azure Kinect and generates RGB-D conbined image.<br>
1) Connect Azure Kinect and your PC.<br>
2) Open AzureKinectCapture folder.<br>
3) Run <b>RTC_Server.exe</b><br>
4) Enter your unique Streaming ID in the text area.<br>
(Please be careful not to duplicate this ID with other users!!)<br>
5) Click setting button.<br>
  <img src="/images/01.png" alt="" width="400"><br><br>
6) Set resolution and FPS to:<br>
　Rsolution: 960x540　<br>
　FPS: 20 <br>
7) Turn On <b>Aut rejoin</b> ir it's necessary.<br>
8) Click check button at right buttom of the window.<br>
  <img src="/images/02.png" alt="" width="400"><br><br>
9) Select <b>UnityCam</b> installed beforehand.<br>
10) Click Join button.<br>
  <img src="/images/03.png" alt="" width="400"><br><br>
11) RGB-D Capturing is started.<br>
  <img src="/images/04.png" alt="" width="400"><br><br>

## Hologram Viewer (AR Device Side)
1) Install apk into your Smartphone (Android).<br>
2) Enter the same Streaming ID that you entered in the PC app.<br>
3) Tap <b>Connect</b> button.<br>

# Give Me Your Feedback
I'm glad if you'll give me feedback, or tag me when you share the video of your experience on SNS or other web-media.<br><br>
<b>Contact Me</b><br>
Twitter: @Tks_Yoshinaga (https://twitter.com/Tks_Yoshinaga)<br>
LinkedIn: Takashi Yoshinaga (https://www.linkedin.com/in/tks-yoshinaga/?locale=en_US)<br>
Instagram: tks_yoshinaga　(https://www.instagram.com/tks_yoshinaga/)<br>
<br><br>
# Acknowledgments
This application is developed with folowing tools.<br>
### WebRTC Video Chat
https://assetstore.unity.com/packages/tools/network/webrtc-video-chat-68030
<br>
### UnityCam
https://github.com/mrayy/UnityCam
<br>
### AzureKinect SDK
https://github.com/microsoft/Azure-Kinect-Sensor-SDK
<br>
