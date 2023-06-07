# HoloTuberKit WebRTC
Simple Volumetric Video capture &amp; AR visualizer. <br>
The capture app is compatible with Windows 10 (with AzureKinect) and iOS (with True Depth Camera).<br>
Viewer apps are compatible with following platforms.<br>
(1) XREAL(Nreal) Light<br>
(2) ARCore(Android)/ ARKit(iOS)<br>
(3) Meta Quest<br>
　-Android Phone and Quest must be developer mode.<br>
(4) LookingGlass Portrait<br>
　-For using LookingGlass, please instal LookingGlass Bridge.
([LookingGlass Bridge](https://lookingglassfactory.com/software/looking-glass-bridge))
<br><br>
[YouTube Video]<br>
[![](https://img.youtube.com/vi/m_uFsbNz-Ko/0.jpg)](https://www.youtube.com/watch?v=m_uFsbNz-Ko)
<br><br>
## Download Page
https://github.com/HoloTuberKit/HoloTuberKit-WebRTC-for-AzureKinect/releases/tag/v1.2.0
<br><br>

# Requirements
## For Kinect User 
<b>Azure Kinect Sensor SDK v1.4.1</b><br>
https://github.com/microsoft/Azure-Kinect-Sensor-SDK/blob/develop/docs/usage.md
<br>
## For TrueDepth Camera User (iPhone X~)
<b>Test Flight</b><br>
https://apps.apple.com/jp/app/testflight/id899247664
<br>
Send me an e-mail for sign up. I'll send you invite to iOS app after receiving your e-mail.
<br>
tks.yoshinaga[at]gmail.com
<br><br>

# How To Use
## Capture Application for Kinect
This application captures RGB and Depth image from Azure Kinect.<br>
1) Connect Azure Kinect and your PC.<br>
2) Open <b>HoloTuber_Server</b> folder.<br>
3) Run <b>HoloTuber_RtcServer.exe</b><br>
4) Enter your unique Streaming ID in the text area.<br>
(Please be careful not to duplicate this ID with other users!!)<br>
5) Click <b>Start</b> button.<br>
  <img src="/images/01.png" alt="" width="400"><br><br>
6) Capturing and steraming are started.<br>
  <img src="/images/02.png" alt="" width="400"><br><br>
## Capture Application for TrueDepth Camera
This application captures RGB and Depth image from TrueDepth Camera of iOS device.<br>
1) Open <b>HoloSender</b> app.<br>
2) Enter your unique Streaming ID in the text area.<br>
(Please be careful not to duplicate this ID with other users!!)<br>
3) Tap <b>Connect</b> button.<br>
4) Capturing and steraming are started.<br><br>

## Viewer Applications (ARCore/NrealLight/LookingGlass)
1) Install application on your devide.<br>
　- ARCore/Nreal/Quest: Install compatible apk.<br>
　- LookingGlass: Unzip LKG_WRTC_HoloTuberKit.zip.<br>
　- iOS: Send an e-mail for sign up. (tks.yoshinaga[at]gmail.com)
2) Launch application<br>
　- ARCore/ARKit/Nreal/Quest: HoloTuber(WRTC).<br>
　- LookingGlass: HoloTuberKit.exe.<br>
2) Enter the same Streaming ID that you entered in the capture app.<br>
3) Tap <b>Connect</b> button or enter key of vertual keyboard.<br>

# Give Me Your Feedback
I'm glad if you'll give me feedback, or tag me or use hash tag, #HoloTuberKit, when you share the video of your experience on social media or other web-media.<br><br>
<b>Contact Me</b><br>
Twitter: @Tks_Yoshinaga (https://twitter.com/Tks_Yoshinaga)<br>
LinkedIn: Takashi Yoshinaga (https://www.linkedin.com/in/tks-yoshinaga/?locale=en_US)<br>
Instagram: tks_yoshinaga　(https://www.instagram.com/tks_yoshinaga/)<br>
# If you have any questions.
There is the channel of HoloTuber Kit on Discord of AR_Fukuoka.<br>
Feel free to join us!<br>
https://discord.gg/XzrPmgGbfn
<br><br>
<br>
