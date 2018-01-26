# DirectX 12 Step by Step

This project also portted from the example of [DirectX 12 official MSDN website] in order to easy know every parts of code and how does it work.

## What you can know

 - Create a basic window.
 - Initialize the pipeline and assets for DirectX 12.
 - Create your first object in view.
 - Create and compile your first shader with HLSL.
 - Transform your object.
 - Load your assets(like texture) and apply on your object.
 - Create a light.

## Preparation
 - **[Visual Studio 2017]**
    - [Visual Studio Code] can be the editor, but you still install Visual Studio 2017. Because we need to use MSBuild to compile your code. For more detail, you can reference [this Blog(Chinese Tranditional)] of mine.
- **[Windows 10 SDK]**
- **[Graphic Card]**
    - Please maks sure the drive of your graphic card is compatible with WDDM 2.0(or above).  For more detail, please see the introduction on MSDN.
- **[DirectX 12 Helper Header]**
    - You can download it from the official webside. It helps you to easy initialize DirectX 12 component.
    - NOTE :  We also put it in the example project, but not guarentee it is latest if there is any update from official.

## Lessons
 - [X] **Lesson 1** : [Create a new project](https://github.com/kw0006667/DirectX12-StepByStep/wiki/Create-a-new-project)
 - [X] **Lesson 2** : [Create and show a basic window](https://github.com/kw0006667/DirectX12-StepByStep/wiki/Create-and-show-a-basic-window)
 - [ ] Lesson 3 : Initialize D3D12 components


## Feedback
If you have any feedback or you want to know more details about the lessons, please create an issue withl lesson's number. I will add more explaination in the comments or markdown feils.


[DirectX 12 official MSDN website]: <https://msdn.microsoft.com/en-us/library/windows/desktop/mt186624(v=vs.85).aspx>
[Visual Studio 2017]: <https://www.visualstudio.com/downloads/>
[Visual Studio Code]: <https://code.visualstudio.com/>
[this blog(Chinese Tranditional)]: <https://kw0006667.wordpress.com/2017/01/31/%e9%80%8f%e9%81%8e-msbuild-%e5%9c%a8-visual-studio-code-%e7%b7%a8%e8%bc%af%e5%9f%b7%e8%a1%8c-cc/>
[Windows 10 SDK]: <https://developer.microsoft.com/en-us/windows/downloads/windows-10-sdk>
[Graphic Card]: <https://msdn.microsoft.com/en-us/library/windows/desktop/dn899118(v=vs.85).aspx>
[DirectX 12 Helper Header]: <https://msdn.microsoft.com/en-us/library/windows/desktop/dn708058(v=vs.85).aspx>