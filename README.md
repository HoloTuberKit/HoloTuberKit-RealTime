# HoloTuberKit
HoloTuberKit is a simple solution for volumetric video capture and AR visualization. I offer both capture and viewer apps compatible with various platforms:

## Capture Apps Compatibility
1. True Depth Camera(For iOS Devices. iPhoneX or newer / iPad Pro)<br>
Open [AppStore](https://apps.apple.com/us/app/holotuberkit/id6449902663) to install the application.

2. Azure Kinect<br>
(*)For Windows. Ensure to install [Azure Kinect Sensor SDK v1.4.1](https://github.com/microsoft/Azure-Kinect-Sensor-SDK/blob/develop/docs/usage.md).

## Viewer Apps Compatibility
1. XREAL(Nreal) Light
2. Android Phone<br>
(*)ARCore compatibility is required. Also make sure Developer mode is turned on.
3. iPhone/iPad (ARKit compatibility is required)<br>
(*)This will be included in the Sender app. [AppStore](https://apps.apple.com/us/app/holotuberkit/id6449902663) 
4. Meta Quest<br>
(*)Make sure Developer mode is turned on for your Meta Quest device.
<br>See https://developer.oculus.com/documentation/native/android/mobile-device-setup/<br>
Also, please use [SideQuest](https://sidequestvr.com) to install the application.
5. LookingGlass Portrait<br>
(*)For Windows. Please install [LookingGlass Bridge](https://lookingglassfactory.com/software/looking-glass-bridge).

Check out the YouTube demo video for reference.

[![YouTube Video](https://img.youtube.com/vi/wJfHrD1ZOIo/0.jpg)](https://www.youtube.com/watch?v=wJfHrD1ZOIo)
<br><br>

# Download Page
Visit [this link](https://github.com/HoloTuberKit/HoloTuberKit-RealTime/releases/tag/v1.3.0) for download.<br><br>

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
   - iOS: Download the app from AppStore.
2. Launch the application.
   - Android/iOS/Nreal/Quest: Start HoloTuber(WRTC).
   - LookingGlass: Run HoloTuberKit.exe.
3. Enter the same Streaming ID that user of sender side entered in the capture app.
4. Tap the **Connect** button or hit the **Enter Key** of the virtual keyboard.

Follow these steps to utilize the viewer applications effectively.

# Known Issue
### 1.Connection Error  
In highly secure network environments, it may not be possible to obtain the device's IP address, which can prevent point cloud streaming. In such cases, please use tethering from a smartphone or other means to stream.  

### 2.FireWallSetting for LookingGlass App  
When running the Windows version of the Looking Glass app for the first time, a dialog will appear asking whether to allow the app to connect to the network.  
If this appears within the Looking Glass display, the text may be very difficult to read, but please **CLICK the BUTTON on the LEFT**　to allow the connection.  
If you accidentally click the button on the right, please remove "holotuberkit.exe" from the list of firewall apps.  
<img src="https://github.com/HoloTuberKit/HoloTuberKit-RealTime/blob/master/images/FireWallSetting.png?raw=true" alt="Firewall Setting" width="360"/>


# Give Me Your Feedback
I'm glad if you'll give me feedback, or tag me or use hash tag, #HoloTuberKit, when you share the video of your experience on social media or other web-media.<br><br>
<b>Contact Me</b><br>
Twitter: @Tks_Yoshinaga (https://twitter.com/Tks_Yoshinaga or https://twitter.com/Taka_Yoshinaga)<br>
LinkedIn: Takashi Yoshinaga (https://www.linkedin.com/in/tks-yoshinaga/?locale=en_US)<br>

# Join Our Discord Server
There is the channel of HoloTuber Kit on Discord of AR_Fukuoka.<br>
Feel free to join us!<br>
https://discord.gg/XzrPmgGbfn
<br><br>
<br>
