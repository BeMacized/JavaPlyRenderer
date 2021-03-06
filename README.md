# SimplePlyRenderer

A simple tool that can render PLY models to an image.
There is currently no texture support.

![preview image](https://i.imgur.com/tWyJLdC.png)

### Usage

```
Simple PLY Renderer
Author: Bodhi Mulders (BeMacized)

Usage: java -jar SimplePlyRenderer.jar <inputModel> [options]
Parameters:

-h, --help:
        Show this help text

-o,  --output <outputFile>
        Specify what file to output the rendered image to (Default render.png)

-res, --resolution <resolution>
        Specify what resolution the resulting image will be (Default 512)

-rot, --rotation <x rotation,y rotation,z rotation>
        Specify how the model should be rotated (Default '0,0,0')

-v, --verbose
        Enables verbose behaviour

-s, --style <SILHOUETTE|DEPTH_MAP|DEPTH_MAP_INVERTED|AXIS_RGB|AXIS_RGB_INVERTED>
        Specify the render style out of the available options (Default 'SILHOUETTE')

```