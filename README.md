# x64dbgpy-screen-recorder

PyQt5 plugin for recording your screen while you use x64debugger.

using modded version of [https://github.com/rdp/screen-capture-recorder-to-video-windows-free]()
Record full hd to mp4 using ffmpeg


**Howto**

build and put the *.dp32 / *.dp64 together with plugins folder to the equal in x64dbg plugin folders 

*.dp32 / *.dp64

Add ffmpeg in  plugins/recorder/bin to Os PATH

Register filter with batch file located in plugins/recorder folder.

screen-capture-recorder.dll

screen-capture-recorder-x64.dll

Remember to unregister filter and re register register filter if you move filters to another folder some day.




**Needed**
[https://github.com/x64dbg/PyQt5]()

[https://github.com/x64dbg/x64dbgpy]()

Use vs2013 same as x64dbg to avoid runtime error.

python 2.7.x x86/x64(depend on your needs)

you should download the The Combined Community Codec Pack, its really minimal and have x64player and mp4 / mkv codecs.

http://www.cccp-project.net/




**Needed**
can run outside x64dbg also :)

[https://github.com/techbliss/Screen_Recorder_x64dbg/tree/master/plugins/recorder]()



**Prebuild Plugin**

[https://github.com/techbliss/Screen_Recorder_x64dbg/releases/tag/1]()

**Thx**
Roger for making capture filters
mr.exodia for making x64dbg together with others
Tomer Zait for starting x64dbgpy
ffmpeg



