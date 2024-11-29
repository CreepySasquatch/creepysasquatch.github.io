---
layout: default
---

### Guides are a work in progress and will be updated over time


### PDF versions of guides can be found [here](https://github.com/CreepySasquatch/reshade-guides)

* * *

<details>
<summary><b>How to setup HDR with ReShade</b></summary><br/>


	### Using Special K with Lilium's Inverse Tone Mapping	


	**WARNING: DO NOT USE WITH RenoDX!!!** 
	> RenoDX does not work with RTGI or other shaders that don't play well with HDR.


	**This guide is currently only tested with DirectX 11 games.**	

	**If the game supports HDR, make sure HDR is turned off within the game's settings before continuing.**

	> The purpose of this guide is to help you get HDR working with ReShade shaders that don't like HDR, such as RTGI. 
	>
	> Some games may require additional steps. Use with other mods or tools not supported.

	> **Note: Otis' Camera Tools are generally not compatible with SpecialK. Use Lilium's fork of DXVK or Lilium's AutoHDR addon instead. 
	> These methods are currently not covered in this guide but may be added in the future.

	**1. Download the latest version of the Special K installer from the Special K Discord and install Special K**
	- [Special K Discord Invite](https://discord.gg/SpecialK)

	- Installer will be found under the installers channel

	- **OPTIONAL: Configure SK so it auto updates anytime a new installer is posted on the SK Discord**
	![image1](https://github.com/CreepySasquatch/creepysasquatch.github.io/tree/main/GuideImages/media/image1.png)

	**2. Launch the game from the SK Launcher by clicking on it, then click Play.**
	![image2](https://github.com/CreepySasquatch/creepysasquatch.github.io/tree/main/GuideImages/media/image2.png)


	**3. You should see the Special K bar on top of your screen when the game launches. 


	**4. Press Ctrl + Shift + Backspace to open the Special K menu**


	**5. Click HDR > HDR Setup > Click the Radial next to scRGB**
	![image3](https://github.com/CreepySasquatch/creepysasquatch.github.io/tree/main/GuideImages/media/image3.png)


	**6. Press Alt + Enter a few times to activate HDR. If this doesn't work, exit the game and restart it from the Special K launcher again.**



	> If you have already calibrated HDR within SpecialK continue onto Step 7.

	**A. Open the SK menu > HDR > HDR Setup**


	**B. Click on Profile Display Capabilities to calibrate Special K to your monitor.**
	![image4](https://github.com/CreepySasquatch/creepysasquatch.github.io/tree/main/GuideImages/media/image4.png)


	**C. Make sure sRGB Inverse is selected under Advanced, otherwise the test pattern won't show up.** 
	- After your display is calibrated, you won't need to do this step ever again in Special K unless you get a new monitor.
	![image5](https://github.com/CreepySasquatch/creepysasquatch.github.io/tree/main/GuideImages/media/image5.png)

	
	**7. TO BE CONTINUED...**

</details>