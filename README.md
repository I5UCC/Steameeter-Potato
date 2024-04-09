# <img src="https://github.com/I5UCC/SVRVoicemeeter/blob/a73c7b4a7f7addffda46029e3589eb86446cb393/Assets/_Res/icon_40x40.png" width="32" height="32"> SteaMeeter-Potato [![Github All Releases](https://img.shields.io/github/downloads/i5ucc/Steameeter/total.svg)](https://github.com/I5UCC/Steameeter/releases/latest) <a href='https://ko-fi.com/i5ucc' target='_blank'><img height='35' style='border:0px;height:25px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' />
SteamVR Dashboard Application that gives you control over the Virtual Inputs of ***Voicemeeter Potato***.

This program will load the XML-File ***vr.xml*** on SteamVR startup and when SteamVR Closes will load in ***default.xml***. You can export those xml files with Voicemeeter by Configuring Voicemeeter for both cases then Menu > Save Settings...

### [<img src="https://assets-global.website-files.com/6257adef93867e50d84d30e2/636e0a6ca814282eca7172c6_icon_clyde_white_RGB.svg"  width="20" height="20"> Discord Support Server](https://discord.gg/rqcWHje3hn)

![image](https://github.com/I5UCC/Steameeter-Potato/assets/43730681/75ee2ec5-ae64-42d2-a4a1-2f275b9d7581)

Currently only supports control of the Virtual inputs, this may expand later.

### OSCQuery support for VRChat

https://github.com/I5UCC/VRCVoiceMeeterControl/assets/43730681/d8f16c9c-84de-4aa2-820f-de59572e04fa

Will listen to following endpoints:

| Parameter      | Description |
| -------------- | --------------- |
| /avatar/parameters/sm/gain/VAIO | Control gain of VAIO virtual input |
| /avatar/parameters/sm/gain/AUX | Control gain of AUX virtual input |
| /avatar/parameters/sm/gain/VAIO3 | Control gain of VAIO3 virtual input |
| /avatar/parameters/sm/restart | Restarts the Audio Engine and fetches current audio Settings to Dashboard/OSC |
| /avatar/parameters/sm/profile/0  | Load vr.xml |
| /avatar/parameters/sm/profile/1 | Load profile1.xml |
| /avatar/parameters/sm/profile/2 | Load profile2.xml |
| /avatar/parameters/sm/profile/3 | Load profile3.xml |
| /avatar/parameters/sm/media/next | Media button Next |
| /avatar/parameters/sm/media/previous  | Media button Previous |
| /avatar/parameters/sm/media/playpause  | Media button Play/Pause |

# Credit
[Otter-Co's](https://github.com/Otter-Co) for [Turnsignal](https://github.com/Otter-Co/TurnSignal). Studying their Project made this alot easier. </br>
[benotter](https://github.com/benotter) for [OVRLay](https://github.com/benotter/OVRLay).</br>
[bobhelander](https://github.com/bobhelander) for [VoicemeeterRemote](https://github.com/bobhelander/VoicemeeterRemote)
