# HoloTuberKit WebRTC for AzureKinect
Simple Volumetric Video capture &amp; AR visualizer for Azure Kinect. 
The capture app is compatible with Windows 10.<br>
Viewer apps are compatible with following platforms.<br>
(1) Nreal Light<br>
(2) ARCore(Android)<br>
(3) Meta Quest<br>
　-Android Phone and Quest must be developer mode.<br>
(4) HoloSDK(Windows)<br>
　-For using HoloSDK app, please instal HoloSDK.(https://www.holo-sdk.com/)
<br><br>
[YouTube Video]<br>
[![](https://img.youtube.com/vi/m_uFsbNz-Ko/0.jpg)](https://www.youtube.com/watch?v=m_uFsbNz-Ko)
<br><br>
You can try also YouTube Live version from below.<br>
https://github.com/HoloTuberKit/HoloTuberKit-for-AzureKinect
<br><br>
## Download Page
https://github.com/HoloTuberKit/HoloTuberKit-WebRTC-for-AzureKinect/releases/tag/v1.0.0
<br><br>

# Requirements
## Azure Kinect Sensor SDK v1.4.1
https://github.com/microsoft/Azure-Kinect-Sensor-SDK/blob/develop/docs/usage.md
<br><br>

# How To Use
## Capture APplication (PC side)
This application captures RGB and Depth image from Azure Kinect and generates RGB-D conbined image.<br>
1) Connect Azure Kinect and your PC.<br>
2) Open <b>HoloTuber_Server</b> folder.<br>
3) Run <b>HoloTuber_RtcServer.exe</b><br>
4) Enter your unique Streaming ID in the text area.<br>
(Please be careful not to duplicate this ID with other users!!)<br>
5) Click <b>Start</b> button.<br>
  <img src="/images/01.png" alt="" width="400"><br><br>
6) Capturing and steraming are started.<br>
  <img src="/images/02.png" alt="" width="400"><br><br>

## Viewer Applications (ARCore/NrealLight/HoloSDK)
1) Install application on your devide.<br>
　- ARCore/Nreal/Quest: Install compatible apk.<br>
　- HoloSDK: Unzip HoloSDK_WRTC_HoloTuberKit.zip.<br>
2) Launch application<br>
　- ARCore/Nreal/Quest: HoloTuber(WRTC).<br>
　- HoloSDK: HoloTuberKit.exe.<br>
2) Enter the same Streaming ID that you entered in the PC app.<br>
3) Tap <b>Connect</b> button.<br>

# Give Me Your Feedback
I'm glad if you'll give me feedback, or tag me when you share the video of your experience on SNS or other web-media.<br><br>
<b>Contact Me</b><br>
Twitter: @Tks_Yoshinaga (https://twitter.com/Tks_Yoshinaga)<br>
LinkedIn: Takashi Yoshinaga (https://www.linkedin.com/in/tks-yoshinaga/?locale=en_US)<br>
Instagram: tks_yoshinaga　(https://www.instagram.com/tks_yoshinaga/)<br>
<br><br>
<br>
