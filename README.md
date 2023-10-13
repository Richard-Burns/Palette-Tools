# Palette-Tools
A collection of TouchDesigner tools that can be used in the palette

## BlockGlitch
A block glitch image filter that works off rows and columns and can affect different colour channels. A good tip is to stack multiples of this same component.

## BrokenVHS
A VHS shader with some extra things added on top of it to give it a bit more depth.
This component is based off the following shadertoy shader which has been confirmed for commercial use by it's original author:
https://www.shadertoy.com/view/XtK3W3

## CameraFrustrum
The standard camera with the option to display a frustrum inside.

## DroneCamera
A camera tool that allows you to use a joystick to control the camera like a drone. L and R triggers move up and down with the analog sticks moving and rotating.

## FilmFilter
Creates something similar to Notch's film filter effect. Chromatic abberation on the edges and a bit of Luma blur on a ramp.

## LineGarbler
A glitch effect that takes rows or columns of the image and displaces them. A good tip for using this is to threshold the image to only act on the parts you want.

## LTCEmulator
A tool for taking a custom timeline in TouchDesigner and converting the timelines frame to Timecode in the same format the LTC In CHOP would work.
It's possible to do this using LTC Out > LTC In but that doesn't seem to support offsets like this component does.

## PerspectiveToOrthographic
A tool for re-mapping SOPs from a perspective camera to an orthographic one. This is particularly useful for situations where you want to do 3D laser effects.

## PointCloudClipper
This is an RGB Key that works with 32-bit TOPs. It's very useful when clipping pointclouds outside the 0-1 limit.

## PointCloudToPLY
Takes an XYZ TOP and an RGB TOP and allows you to save it out as a PLY file for use with other software.

## SimpleBloom
A basic fake bloom component that is very lightweight compared to other bloom solutions.

## TextGarbler
A text garbler for animation of garbled text. You can also type on text and have a flashing cursor at the end. This COMP is good for when you need hacker style typing on text or matrix style garbling and other effects like that.

## TracelineMaker
A tool for creating trace lines from SOPs and animating them. Open the viewer and click on points to start creating a trace. Click Clear Trace to clear. 
For multiple tracelines you can hit the export pulse parameters to export either an animated traceline or a static full length one ready for use with a Carve SOP.