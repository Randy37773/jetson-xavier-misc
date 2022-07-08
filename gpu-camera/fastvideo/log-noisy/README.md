# information about distorted-images problem

I try to acquire images with ximea-mu181cr-on camera on jetson-xavier-nx using [fastvideo's gpu-camera-sample](https://github.com/fastvideo/gpu-camera-sample), but images are distorted.

The ximea-camera is working with ximea's xiCamTool (despite some warnings in the logs), picture quality is good.
The ximea-camera is "raw-working" with [fastvideo's gpu-camera-sample](https://github.com/fastvideo/gpu-camera-sample), but unpacking the raw-data to pictures seems not to work for now.

Retrieved images are distorted. In this place I try to accumulate information for support.

In log-noisy are information about
* how I built gpu-camera-sample (CMakeLists.txt),
* directory listing of the executable (gpu-camera-sample--GPUCameraSampla_Arm64--release.txt)
* directory listing of OtherLibsLinux (gpu-camera-sample--OtherLibsLinux.txt)
* screenshot of the application (Screenshot-from-2022-07-08-03-17-21.png)
* terminal output of the application (GPUCameraSample.log)
* recorded pictures of a red light (Frame_*.*)

In xiCamTool are information about
* the ximea camera configuration I used for recording (cam-conf-90deg-mu181cr-on---red.xicamera)
* my default ximea camera configuration (cam-conf-90deg-mu181cr-on.xicamera)
* a screenshot of xiCamTool (Screenshot---xiCamTool.png)
* terminal output of xiCamTool (xiCamTool--mu181cr-on--90deg----red-log.txt)
* a recorded picture of a red light (mu181cr-on--90deg---red.png)