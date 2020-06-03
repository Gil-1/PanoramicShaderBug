# PanoramicShaderBug

Unity project to show the panoramic shader that is not compatible with the new XR plugin.
This was created with Unity 2019.3.15f1
I only added the XR Plugin manager (3.2.10) and added the Oculus provider.

To see what's expected I checked the Unity documentation : https://docs.unity3d.com/Manual/VideoPanoramic.html
Here it says "(menu: Edit > Project Settings, then select the Player category, and open the XR Settings panel)"

Since this part of the settings is deprecated the option "3D Layout" is not available in the shader as he doesn't take into account the new XR plugin.
There is a "PanoramicBug" material in the asset folder to see what's up.

Also, I hope the "3D Layout" will be available for both mapping solutions.
