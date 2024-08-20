[Page]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Libs.Engine/blob/main/Project/Systems/SDL.md

[Page Home]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Libs.Engine/blob/main/README.md
[Page Project Home]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Libs.Engine/blob/main/Project/Project_Home.md
[Page Learn Home]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Libs.Engine/blob/main/Learn/Learn_Home.md
[Page Changes Home]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Libs.Engine/blob/main/Changes/Changes_Home.md

[Page DesignLayout ThirdPartyWrapSys]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Coding/ThirdPartyWrapperSys_DL.md
[Page DesignLayout RealmsOOP]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Coding/RealmsOOP_DL.md
[Page DesignLayout ThirdPartyWrap]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Coding/ThirdPartyWrapper_DL.md
[Page SDL]:https://www.libsdl.org

[Sec Welcome]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Libs.Engine/blob/main/Project/Systems/SDL.md#welcome
[Sec Details]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Libs.Engine/blob/main/Project/Systems/SDL.md#system-details
[Sec Features]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Libs.Engine/blob/main/Project/Systems/SDL.md#features

# Realms Tutorial Collections: "Realms Engine" - Systems - SDL Wrap System

## Site Index

- [Home][Page Home]
	- [Project][Page Project Home]
		- Library Host System (You are here)
	- [Learning][Page Learn Home]
	- [Changes][Page Changes Home]

## Page Index

- Page
	- [Welcome][Sec Welcome]
	- [System Details][Sec Details]
	- [Features][Sec Features]

### Welcome

Welcome to the SDL Wrap System's documentation page. This page is dedicated to helping you understand the system and its features. However please note that for understanding how to use the project you should check out [Learning][Page Learn Home] for all the dedicated learning for the given project.

### System Details

- Details
	- Name: SDL Wrap
	- SystemID: Engine.SDL
	- IDPiece: SDL
	- Version: V 1.0.0

This system is a dedicated [Third Party Wrapper System][Page DesignLayout ThirdPartyWrapSys] for wrapping around [SDL2][Page SDL], please note that our current focuse is on OpenGL. We may at a later date wrap around the other graphics systems. 

Please note that we claim no rights over SDL2 or its development team. This system provides a layer to bring the SDL functions more understandable and will allow us to use the [Realms C OOP][Page DesignLayout RealmsOOP].

### Features

|Feature Name|Feature ID|Status|Version|Desc|
|:---|:---|:---|:---|:---|
|SDL Window Wrap|SDL.Window|Active|V 1.0|This feature is a [C OOP Wrapper][Page DesignLayout ThirdPartyWrap] used to interact with SDL Windows|
|SDL OpenGL Context Wrap|SDL.GLContext|Active|V 1.0|This feature is a [C OOP Wrapper][Page DesignLayout ThirdPartyWrap] used to interact with SDL's OpenGL features|
