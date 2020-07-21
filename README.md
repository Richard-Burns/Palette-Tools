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