# Tobii Eye Tracking for Unreal Engine 4.27

*Disclaimer: I am not the original programmer for this, finding the SDK is an absolute pain, I don't get responses from Tobii when I send requests. found a 4.23 version and updated for 4.27, *

https://github.com/litruv/TobiiEyetracking/blob/4.27/Source/TobiiCore/Public/TobiiTypes.h#L215
for the one change I did make.

## To get started:

### Prerequisites:
Tobii Unreal Engine SDK requires the following setup on your computer:

* Unreal Engine 4.27 or later
* Windows 10, 8.1, or 7
* Target build platform Windows32/64
* Tobii Eye Tracking Core Software (either downloaded install bundle for peripheral eye tracker, or pre-installed on integrated systems)
* Tobii consumer eye tracker peripheral or built-in device.

### Add the Plugin to your Project:
Unzip this package into the Plugins folder in your project. The uplugin file should be located here:

	MyProject/Plugins/TobiiEyetracking/TobiiEyetracking.uplugin

Launch your project again and follow the prompts from there to get to the samples and try out some 
eyetracked interactions!

If you are developing for desktop, a good place to start is the Tobii
Unreal Engine SDK section on for desktop [Tobii Developer Zone] (https://developer.tobii.com/pc-gaming/unreal-engine-sdk/api-reference/).

If you are focusing on VR have a look at the VR section of [Tobii Developer Zone] (https://developer.tobii.com/vr/develop/ue4/api/introduction/).

**Have Fun!**
