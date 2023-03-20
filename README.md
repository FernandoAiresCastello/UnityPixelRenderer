# Unity Pixel Renderer
This is a very simple C# script for the Unity engine that allows you to programmatically render individual pixels on the screen, without any filtering or anti-aliasing, generating just pixel perfect images.

All you need in your scene is a Main Camera with a Canvas object as a child, and the Canvas needs to have a Raw Image component. Then just attach the PixelRenderer script to the Canvas.

In the example included, the Update() method calls RenderTestFrame() which sets each every pixel on the screen to a random color, producing a pixelated and colorful "TV static" effect, as seen in the screenshot below.

![Screenshot](https://github.com/FernandoAiresCastello/UnityPixelRenderer/blob/master/screenshot.png?raw=true)