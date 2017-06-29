# ROSVR-leapmotion
The purpose of this project to make adaptation of different LeapMotion tools for linux environment.

# Getting Started
You must be sure that ***LeapMotionSDK*** and ***LeapMotionCoreAssets*** have the same version.
- Download SDK package from [**LeapMotion SDK**](https://developer.leapmotion.com/sdk/v2/) and extract it to some directory
- Use instructions from [**LeapMotion RPM package**](https://github.com/bugzy/leap-fedora-rpm) to generate and install LeapMotion RPM
- Move `Plugins` directory from LeapDeveloperKit_*/LeapSDK/lib/UnityAssets to Unity projec assets
- Get git repository from [**LeapMotionCoreAssets**](https://github.com/leapmotion/LeapMotionCoreAssets)
- Change LeapMotionCoreAssets repository tag to desired one
- Move `LeapMotionCoreAssets/Assets/LeapMotion` directory from repository to the Unity project assets
- Export the Unity assets to generate new `.unitypackage` pacakge

# Useful Links
- [**Unity Build #20170606**](https://forum.unity3d.com/threads/unity-on-linux-release-notes-and-known-issues.350256/)
- [**LeapMotion SDK**](https://developer.leapmotion.com/sdk/v2/)
- [**LeapMotion RPM package**](https://github.com/bugzy/leap-fedora-rpm)
- [**LeapMotionCoreAssets**](https://github.com/leapmotion/LeapMotionCoreAssets)

