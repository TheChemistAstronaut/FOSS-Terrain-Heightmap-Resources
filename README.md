# Blender
https://www.youtube.com/watch?v=ekogw2Zm20Y
https://youtu.be/y7bH2bXKyTk

- Use ANT landscapes to generate mesh (Ridged Mfractal works well)
- Use blender sculpting to refine as needed
- From top view, create orthographic camera with same orthographic scale as mesh.
- Enable Z output data for Render Layers in compositing view
- In compositing, output Depth into Normalize, output Normalize into Invert (Color Input), and output from invert into composite image.
- In camera object's camera tab in color management - view transofrm set to RAW
- When "SAVE AS" the rendered image, ensure that color management set to RAW as well.
