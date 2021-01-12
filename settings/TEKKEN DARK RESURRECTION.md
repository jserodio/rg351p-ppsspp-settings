# TEKKEN DARK RESURRECTION
## 30/60 FPS 100% speed in battle - 60/60 FPS in Menus
### Minor FPS drops in prebattle.

The key here is to play at 30 FPS to have an stable framerate.
The problem is that the camera scenes run at 30 FPS, so if you frameskip at 1, you will get half the speed, which is 15 FPS in camera scenes.
If we run Automatic Frameskip at 1, we solve this at once, we'll get 60/60 FPS on menus, 30/60 FPS in battle, 30/30 in camera scenes.

❎ means OFF or unchecked  
☑️ means ON or checked

Rendering mode |  
------------ | -------------
Backend | **OpenGL**
Mode | **Buffered rendering** 
Simulate block transfer effects | ☑️ 

Framerate control |  
------------ | -------------
Frame skipping | **1**    
Frame skipping type | **Number of Frames**  
Auto Frameskip | ☑️ 
Alternative speed | **Disabled** 
ALternative speed 2 | **Disabled**

Postprocessing effect |  
------------ | -------------
Postprocessing shader #1 | **OFF**

Screen layout |  
------------ | -------------
Fullscreen | ☑️ 

Performance |  
------------ | -------------
Rendering resolution | **Auto(1:1)**  
VSync | ☑️ 
Render duplicate frames to 60 Hz |  ☑️ 
Buffer graphics commands (faster, input lag) | **No buffer*
Hardware transform | ☑️ 
Software skinning | ☑️ 
Vertex cache | ☑️ 
Clear framebuffers on first use (speedhack) | ❎
Lazy texture catching (speedup) | ☑️
Retain changed textures (sometimes slower) | ❎
Disable slower effects (speedup) | ☑️ 
Spline/Bezier curves quality | **Low**

Texture scaling |  
------------ | -------------
Upscale level | **OFF**  
Upscale type | **xBRZ**  
Deposterize | ❎

Texture filtering |  
------------ | -------------
Anisotropic filtering | **OFF**  
Texture filtering | **Linear**  
Screen scaling filter | **Linear**  

Hack Settings |  
------------ | -------------
Lower resolution for effects (reduces artifacts) | **OFF**  

Overlay information |  
------------ | -------------
Show FPS counter | **Both** (Optional: as you wish)
Show debug statistics | ❎

System Emulation |  
------------ | -------------
Fast memory (unstable) | ☑️
Ignore bad memory acceses | ☑️
I/O timing method | **Fast (lag on slow storage)**
Force real clock sync (slower, less lag) | ❎
Change emulated PSP's CPU clock (unstable) | **333**
