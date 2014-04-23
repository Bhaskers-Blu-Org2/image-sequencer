﻿Image Sequencer
===============

Image Sequencer is an example application demonstrating the use of Nokia Imaging SDK’s Image Aligner and Gif Renderer APIs for creating cinemagraph-style animations in animated GIF format. The application has a set of hard coded image sequences to be used for basis of the alignment and animation. User can manipulate the animation by limiting the animated area to a small rectangular section, and by stabilizing the images in order to eliminate camera shake. Animations with still backgrounds and minor repeated movement are commonly called cinemagraphs.

This example application is hosted in GitHub:
https://github.com/nokia-developer/image-sequencer/

For more information on implementation visit Nokia Lumia Developer's Library: http://developer.nokia.com/resources/library/Lumia/nokia-imaging-sdk/sample-projects/image-sequencer.html

Developed with Microsoft Visual Studio Express 2012 for Windows Phone.

Compatible with:

 * Windows Phone 8.1
 * Windows Phone 8.0

Tested to work on:

 * Nokia Lumia 520
 * Nokia Lumia 1020
 * Nokia Lumia 1520


Instructions
------------

Make sure you have the following installed:

 * Windows 8
 * Visual Studio Express 2012 for Windows Phone
 * Nuget 2.7 or later

To build and run the sample in emulator

1. Open the SLN file:
   File > Open Project, select the solution (.sln postfix) file for the target
   (Windows Phone 8.1, Windows Phone 8.0) you want to use.
2. Select the target 'Emulator' and platform 'x86'.
3. Press F5 to build the project and run it.


If the project does not compile on the first attempt it's possible that you
did not have the required packages yet. With Nuget 2.7 or later the missing
packages are fetched automatically when build process is invoked, so try
building again. If some packages cannot be found there should be an
error stating this in the Output panel in Visual Studio Express.

For more information on deploying and testing applications see:
http://msdn.microsoft.com/library/windowsphone/develop/ff402565(v=vs.105).aspx


About the implementation
------------------------

| Folder | Description |
| ------ | ----------- |
| / | Contains the project file, the license information and this file (README.md) |
| ImageSequencer | Root folder for the implementation files.  |
| ImageSequencer/Assets | Graphic assets like icons and tiles. |
| ImageSequencer/Resources | Localized resources. |
| ImageSequencer/Properties | Application property files. |
| ImageSequencer/Toolkit.Content | Graphics assets for Windows Phone toolkit. |

Important classes:

| Class | Description |
| ----- | ----------- |
| MainPage | Page for displaying the preview animation. |
| ImagePicker | Page for displaying hard coded image sequences and saved GIF files in a grid. |
| GifExporter | Utility class for exporting GIF animations. |


Known issues
------------

 * Application tombstoning is not supported.


License
-------

See the license text file delivered with this project:
https://github.com/nokia-developer/image-sequencer/blob/master/License.txt


Downloads
---------

| Project | Release | Download |
| ------- | --------| -------- |
| Image Sequencer | v1.1 | [image-sequencer-1.1.zip](https://github.com/nokia-developer/image-sequencer/archive/1.1.zip) |
| Image Sequencer | v1.0 | [image-sequencer-1.0.zip](https://github.com/nokia-developer/image-sequencer/archive/1.0.zip) |


Version history
---------------

 * 1.1.0.0: Image Sequencer Silverlight 8.1 version
 * 1.0.0.0: First public release of Image Sequencer
