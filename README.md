# RTB_suite
[![Real-time Bus (RTB)](https://img.shields.io/badge/RTB_Project-FF6699)](https://www.rtb4dcc.de)
[![Real-time Bus (RTB)](https://img.shields.io/badge/RTB_suite-66FF33)](https://github.com/git4dcc/RTB_suite)
[![Apache License 2.0](https://img.shields.io/badge/license-Apache%20License%202.0-lightgray)](https://www.apache.org/licenses/LICENSE-2.0)

**A distributed, PC-based DCC command station and layout control suite.**<br><br>
This software generates real-time DCC commands on a host PC and broadcasts them over a low-latency bus to physical layout hardware. The software is designed to run in a distributed environment communicating via IP network


<details>
<summary>User Guides</summary>

- [User Guide - DE](https://rtb4dcc.de/rtb_minimal_guide_de/)
- [User Guide - EN](https://rtb4dcc.de/rtb_minimal_guide_en/)

</details>


<img src="supplemental/images/Overview.jpg">

## Package versions
```
Filename format: RtbSuite_YYYYMMDD.zip
```
Note: I will manage a maximum of 12 package drops here in GitHub and remove the oldest one as soon as it is reached.

| File | Type | Description |
| --- | --- | --- |
| [RtbSuite_20251214](https://github.com/git4dcc/RTB_suite/blob/main/x64/RtbSuite_20251214.zip) | zip | :white_check_mark: **add:** Zimo MDU protocol for MS/MN decoder updates |
| [RtbSuite_20260115](https://github.com/git4dcc/RTB_suite/blob/main/x64/RtbSuite_20260115.zip) | zip | :white_check_mark: **add:** Zimo DECUP protocol for MX decoder updates |

<br>

## Installation
Download any of the [packages](https://github.com/git4dcc/RTB_suite/tree/main/x64) and unzip into a directory of your choice.

| File | Type | Description |
| --- | --- | --- |
| rtbserver | exe | Central object repository server |
| rtbproxy | exe | Layout proxy agent |
| rtbclient | exe | Universal command line interface |
| rtbz21 | exe | Z21 emulator integrating hand held Roco WLAN Mouse |
| rtbftdi | exe | USB helper program scanning the USB for connected FTDI devices |
| rtbcor | dll | Basic object behavior implementation |
| rtbrpc | dll | Distributed object behavior implementation (publish/subscriber) |
| **FW** | subdir | :file_folder: contains Cxx firmware (.hex) files. Will be installed automatically during startup. |

<br>

## Startup
+ Connect the module via **USB**<br>
+ Start **rtbserver.exe** in a command window
+ Start **rtbproxy.exe** in a command window

You are now up and running.
[Demo Video (German)](https://youtu.be/FtHR6CCo5IE?t=1m6s)

<br>

# YouTube
A couple of YouTube videos on different use-cases (currently German language, but I plan to redo them in english).<br><br>

| Video #1 | Video #2 | Video #3 |
| --- | --- | --- |
| [<img src="https://img.youtube.com/vi/Au-6CpvpdI8/0.jpg" width=310>](https://youtu.be/Au-6CpvpdI8) | [<img src="https://img.youtube.com/vi/YBKRzL3ug-c/0.jpg" width=310>](https://youtu.be/YBKRzL3ug-c) | [<img src="https://img.youtube.com/vi/InFnjWulHMA/0.jpg" width=310>](https://youtu.be/InFnjWulHMA?t=1m0s) |
| Hardware assembly | Automatic decoder detection | My DIY decoder development |

| Video #4 | Video #5 | Video #6 |
| --- | --- | --- |
| [<img src="https://img.youtube.com/vi/afoW1E1A6Zc/0.jpg" width=310>](https://youtu.be/afoW1E1A6Zc) | [<img src="https://img.youtube.com/vi/ZyTRiSBSxrk/0.jpg" width=310>](https://youtu.be/ZyTRiSBSxrk) | [<img src="https://img.youtube.com/vi/AxBWCUPm_NM/0.jpg" width=310>](https://youtu.be/AxBWCUPm_NM) |
| My DIY decoder SW update | Zimo MS/MN decoder SW update | Zimo MX decoder SW update |


This project is intended for hobby use only and is distributed in accordance with the Apache License 2.0 agreement.
