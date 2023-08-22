# HoloTuberKit
HoloTuberKit is a simple solution for volumetric video capture and AR visualization. I offer both capture and viewer apps compatible with various platforms:

## Capture Apps Compatibility
1. Azure Kinect<br>
(*)For Windows. Ensure to install [Azure Kinect Sensor SDK v1.4.1](https://github.com/microsoft/Azure-Kinect-Sensor-SDK/blob/develop/docs/usage.md).
2. True Depth Camera(For iOS Devices. iPhoneX or newer / iPad Pro)<br>
Open [AppStore](https://apps.apple.com/us/app/holosender/id6449902663) to install the application.

## Viewer Apps Compatibility
1. XREAL(Nreal) Light
2. Android Phone<br>
(*)ARCore compatibility is required. Also make sure Developer mode is turned on.
3. iPhone/iPad (ARKit compatibility is required)<br>
(*)This will be included in the Sender app. [AppStore](https://apps.apple.com/us/app/holosender/id6449902663) 
4. Meta Quest<br>
(*)Make sure Developer mode is turned on for your Meta Quest device.
<br>See https://developer.oculus.com/documentation/native/android/mobile-device-setup/<br>
Also, please use [SideQuest](https://sidequestvr.com) to install the application.
5. LookingGlass Portrait<br>
(*)For Windows. Please install [LookingGlass Bridge](https://lookingglassfactory.com/software/looking-glass-bridge).
6. Tilt Five<br>
(*)When using MixCast, please make sure to start MixCast after you have finished entering the connection ID and connecting to the transmission app.
6. ZapBox (iOS)<br>
(*)[ZapBox](https://www.zappar.com/zapbox/) is required. 


Check out the YouTube demo video for reference.

[![YouTube Video](https://img.youtube.com/vi/wJfHrD1ZOIo/0.jpg)](https://www.youtube.com/watch?v=wJfHrD1ZOIo)
<br><br>

# Download Page
Visit [this link](https://github.com/HoloTuberKit/HoloTuberKit-WebRTC-for-AzureKinect/releases/tag/v1.2.0) for download.<br><br>

# How To Use
## 1. Capture Application (Sender Side)
### For Kinect User
This application captures RGB and Depth images from Azure Kinect.

1. Connect Azure Kinect to your PC.
2. Open the **HoloTuber_Server** folder.
3. Run **HoloTuber_RtcServer.exe**.
4. Enter a unique Streaming ID in the text field (Take care not to use an ID already in use by another user).
5. Click the **Start** button.
<br><img src="/images/01.png" alt="" width="400"><br><br>
6. By following the above steps, capturing and streaming will be started.
<br><img src="/images/02.png" alt="" width="400"><br><br>
### For True Depth Camera User
This application captures RGB and Depth images from the TrueDepth Camera of your iOS device.

1. Open the **HoloSender** app.
2. Enter a unique Streaming ID in the text field (Take care not to use an ID already in use by another user).
3. Tap the **Connect** button.

Now, capturing and streaming are initiated.

## 2. Viewer Applications (Receiver Side)
Here's how to operate the viewer applications:

1. Install the application on your device.
   - ARCore/Nreal/Quest: Install the compatible **.apk**.
   - LookingGlass: Unzip **LKG_WRTC_HoloTuberKit.zip**.
   - iOS: Send an email for sign up (**tks.yoshinaga[at]gmail.com**).
2. Launch the application.
   - ARCore/ARKit/Nreal/Quest: Start HoloTuber(WRTC).
   - LookingGlass: Run HoloTuberKit.exe.
3. Enter the same Streaming ID that user of sender side entered in the capture app.
4. Tap the **Connect** button or hit the **Enter Key** of the virtual keyboard.

Follow these steps to utilize the viewer applications effectively.


# Give Me Your Feedback
I'm glad if you'll give me feedback, or tag me or use hash tag, #HoloTuberKit, when you share the video of your experience on social media or other web-media.<br><br>
<b>Contact Me</b><br>
Twitter: @Tks_Yoshinaga (https://twitter.com/Tks_Yoshinaga or https://twitter.com/Taka_Yoshinaga)<br>
LinkedIn: Takashi Yoshinaga (https://www.linkedin.com/in/tks-yoshinaga/?locale=en_US)<br>
Instagram: tks_yoshinaga　(https://www.instagram.com/tks_yoshinaga/)<br>
# Join Our Discord Server
There is the channel of HoloTuber Kit on Discord of AR_Fukuoka.<br>
Feel free to join us!<br>
https://discord.gg/XzrPmgGbfn
<br><br>
<br>
