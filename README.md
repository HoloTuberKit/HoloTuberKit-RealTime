# HoloTuberKit WebRTC for AzureKinect
Simple Volumetric Video capture &amp; AR visualizer for Azure Kinect. 
The capture app is compatible with Windows 10 and the viewer is compatible with Android (ARCore/Vuforia).
<br>
[YouTube Video]<br>
[![](https://img.youtube.com/vi/m_uFsbNz-Ko/0.jpg)](https://www.youtube.com/watch?v=m_uFsbNz-Ko)
<br><br>

# Requirements
<b>・ Azure Kinect Sensor SDK v1.4.0</b> <br>
https://github.com/microsoft/Azure-Kinect-Sensor-SDK/blob/develop/docs/usage.md
<br><br>
<b>・ UnityCam</b> <br>
https://github.com/mrayy/UnityCam
<br>
[Instalation]<br>
(1)Access folder "RunMe First" -> "x64". <br>
(2)Right click on "Register.bat".
(3)Click "Run as Administrator" to register UnityCam plugin in Windows. <br>
<br>
# How To Use
## Hologram Capture
This application captures RGB and Depth image from Azure Kinect and generates RGB-D conbined image.<br>
1) Connect Azure Kinect and your PC.
2) Open AzureKinectCapture folder.
3) Run <b>RTC_Server.exe</b>
4) Enter your unique Streaming ID in the text area.<br>
(Please be careful not to duplicate this ID with other users!!)<br>
5) Click setting button.
  <img src="/images/01.png" alt="" width="400"><br><br>
6) Set resolution and FPS to:<br>
　Rsolution: 960x540　<br>
　FPS: 20 <br>
7) Turn On <b>Aut rejoin</b> ir it's necessary.
8) Click check button at right buttom of the window.
  <img src="/images/02.png" alt="" width="400"><br><br>
9) Select <b>UnityCam</b> installed beforehand.
10) Click Join button.
  <img src="/images/03.png" alt="" width="400"><br><br>
11) RGB-D Capturing is started.
  <img src="/images/04.png" alt="" width="400"><br><br>

## Receiving Hologram (AR Device Side)
1) Install apk into your Smartphone (Android).
2) Enter the same Streaming ID that you entered in the app.
3) Tap <b>Connect</b> button.

# Give Me Your Feedback
I'm glad if you'll give me feedback, or tag me when you share the video of your experience on SNS or other web-media.<br><br>
<b>Contact Me</b><br>
Twitter: @Tks_Yoshinaga (https://twitter.com/Tks_Yoshinaga)<br>
LinkedIn: Takashi Yoshinaga (https://www.linkedin.com/in/tks-yoshinaga/?locale=en_US)<br>
<br>
