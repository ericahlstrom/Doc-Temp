# Finishing Touches
Let's cover a handful of items that you will want to strongly consider implementing for your app prior to submitting and publishing to the Windows Store. 

## What Are App Launchers?
When a user launches your app from the Cliff House there are two different "launchers" that can be presented. The default launcher is a 2D launcher. It looks like a flat window slate and displays the app's splash image over the splash screen background color.

Here's a wide shot of a 2D Launcher:
![2D Launcher](https://raw.githubusercontent.com/ericahlstrom/Doc-Temp/master/images/4-2DLauncher.jpg)
Here's a closer look:
![2D Launcher](https://raw.githubusercontent.com/ericahlstrom/Doc-Temp/master/images/4-2DLauncher2.jpg)
The 2D Launcher is defined by the splash screen image and the splash background color. As of today, the default aspect ratio of the 2D Launcher is taller than the splash screen image which results in horizontal bars being displayed above and below the image. The app title is shown as well in the header bar. More details on how to set the splash screen and splash background color below.

Unique to the Mixed Reality Portal is the 3D Launcher. Once defined in your package manifest file, this replaces the default 2D Launcher with a 3D object of your own design.

Here is a sample 3D Launcher:
![Placeholder](https://raw.githubusercontent.com/ericahlstrom/Doc-Temp/master/images/Placeholder.jpg)
Users can adjust the scale and rotation of your 3D Launcher in addition to placing it wherever they desire within the Cliff House environment. 

## Set the Background Color
Whether you use a 3D Launcher or not, you should consider setting the splash background color to something that matches your app's colors. Besides bars on the 2D Launcher, the splash background color and splash image are also used in the launch animation of an app.

Here is a screen grab of the launch animation showing the orange splash background color set by the app:
![enter image description here](https://raw.githubusercontent.com/ericahlstrom/Doc-Temp/master/images/4-BackgroundColor.jpg)

By default, the background color is set to white. Currently, the background color options in Unity Player Settings for Splash Image do not get set for Windows UWP. To set the splash background color

## Define a Splash Image

## Make a 3D Launcher

## Configure a 3D Launcher


## App Icons 


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwODcyMzk0ODldfQ==
-->