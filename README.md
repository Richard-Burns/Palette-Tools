# Palette-Tools
A collection of TouchDesigner tools that can be used in the palette

## PerspectiveToOrthographic
A tool for re-mapping SOPs from a perspective camera to an orthographic one.

## LTCEmulator
A tool for taking a custom timeline in TouchDesigner and converting the timelines frame to Timecode in the same format the LTC In CHOP would work.
It's possible to do this using LTC Out > LTC In but that doesn't seem to support offsets like this component does.

## TracelineMaker
A tool for creating trace lines from SOPs and animating them. Open the viewer and click on points to start creating a trace. Click Clear Trace to clear. 
For multiple tracelines you can hit the export pulse parameters to export either an animated traceline or a static full length one ready for use with a Carve SOP.

## ArcBallPreviz
A quick helper for setting up a previz environment. Includes dennis from renderpeople and an environment map in the tox.

## DroneCamera
A simple camera tool that allows you to use a joystick to control the camera like a drone. L and R triggers move up and down with the analog sticks moving and rotating.

## PointCloudToPLY
Takes an XYZ TOP and an RGB TOP and allows you to save it out as a PLY file for use with other software.

## TextGarbler
A text garbler for animation of garbled text. You can also type on text and have a flashing cursor at the end. This COMP is good for when you need hacker style typing on text or matrix style garbling and other effects like that.