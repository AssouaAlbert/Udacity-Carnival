# Udacity Carnival
Starter project for the Udacity [VR Developer Nanodegree](http://udacity.com/vr) program.

- Course: Introduction to Virtual Reality
- Project: Udacity Carnival


# About
This project is my first project of the Udacity Course, my name is *Eloumbat Assoua Albert* . The goals of this project are:
* `Customize the wheel of Fortune`:
	* The point values are changd to be higher for smaller wedges lower for larger wedges(e.g. 50, 100, 150, 175, 200)
	* The point value text displayed on each wedge fits within the edge if the wedge.
* `Customize the Coin Toss`:
	* The Min and MAx toss power of the carnival coin toss component are changed to 10 and 13 (Which are in the hidden text; find the hidden).
* `Customize the Score board`:
	*The name on the score board is changed to *Eloumbat Assoua Albert's Score* fits within the edge if the wedge.
* `Customize Plinko`:
	* Change Oscillation Distance on the Plinko, to the value displayed in the scene when you `win` the Coin Toss game.
* `Change the Positions of the Bear`
	* The bear is moved forward, so that it does not fall on the players head when he wins. (When the total score gets to 2000).
* The last step is building and running the project on an android device.
## Installs 
	Note: You should already have downloaded and installed Android Studio and the Java SE Development Kit 8 (JDK)
	- If your anivirus is active, temporally deactivate it as some `*.cs` may be blocked from being run.


### Versions Used
- [Unity LTS Release 2017.4.15](https://unity3d.com/unity/qa/lts-releases?version=2017.4)
- [GVR SDK for Unity v1.170.0](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.170.0)
- [TextMesh Pro](https://assetstore.unity.com/packages/essentials/beta-projects/textmesh-pro-84126) v1.2.2


### Directory Structure
- The Unity project is the child directory of the repository and named according to the associated lesson.
- The Unity project is 'cleaned' and includes the `Assets` folder, the `ProjectSettings` folder, and the `UnityPackageManager` folder.


### GVR SDK for Unity
- `GoogleVR` > `Demos` is not included.
- `GoogleVR` > `GVRVideoPlayer.unitypackage` is not included.
- The `Max Reticle Distance` value for the `GvrReticlePointer` used in the scene is set to `20` instead of the default `10`.
- Scripts applicable to the course have been updated to reflect Unity's API change from `UnityEngine.VR` to `UnityEngine.XR`.

>**Note:** If for any reason you remove and re-import GVR SDK for Unity v1.170.0, make sure you accept any API update pop-up prompts triggered by Unity. Alternatively, you can manually run the API updater (Unity menu `Assets` > `Run API Updater...`) after the import has completed.
