# RTB_suite
[![Real-time Bus (RTB)](https://img.shields.io/badge/RTB_Project-FF6699)](https://www.rtb4dcc.de)
[![Real-time Bus (RTB)](https://img.shields.io/badge/RTB_suite-66FF33)](https://github.com/git4dcc/RTB_suite)
[![Apache License 2.0](https://img.shields.io/badge/license-Apache%20License%202.0-lightgray)](https://www.apache.org/licenses/LICENSE-2.0)

Software Suite for running RTB model railway infrastructure.


<details>
<summary>User Guides</summary>

- [User Guide - DE](https://rtb4dcc.de/rtb_minimal_guide_de/)
- [User Guide - EN](https://rtb4dcc.de/rtb_minimal_guide_en/)

</details>

<img src="supplemental/images/Overview.jpg">

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
| **FW** | subdir | contains Cxx firmware (.hex) files. Will be installed automatically during startup. |



## Package version format
```
Filename format: RTB_suite_YYYYMMDD.zip
```
Note: I will manage a maximum of 12 package drops here in GitHub and remove the oldest one as soon as it is reached.

# YouTube
A couple of YouTube videos on different use-cases (currently German language, but I plan to redo them in english.<br><br>

| Video #1 | Video #2 | Video #3 |
| --- | --- | --- |
| [<img src="https://img.youtube.com/vi/Au-6CpvpdI8/0.jpg" width=310>](https://youtu.be/Au-6CpvpdI8) | [<img src="https://img.youtube.com/vi/YBKRzL3ug-c/0.jpg" width=310>](https://youtu.be/YBKRzL3ug-c) | [<img src="https://img.youtube.com/vi/InFnjWulHMA/0.jpg" width=310>](https://youtu.be/InFnjWulHMA) |
| Hardware assembly | Automatic decoder detection | Use for my DIY decoder development |

| Video #4 | Video #5 |
| --- | --- |
| [<img src="https://img.youtube.com/vi/afoW1E1A6Zc/0.jpg" width=310>](https://youtu.be/afoW1E1A6Zc) | [<img src="https://img.youtube.com/vi/ZyTRiSBSxrk/0.jpg" width=310>](https://youtu.be/ZyTRiSBSxrk) |
| My DIY decoder SW update | Zimo MS/MN decoder SW update |


This project is intended for hobby use only and is distributed in accordance with the Apache License 2.0 agreement.
