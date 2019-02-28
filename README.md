# Ryujinx-OGL-Demos
A small collection of switch test apps for testing features in ryujinx.  
Compile using devkinpro and the make files.  
Fair warning the code is very messy as does very little in most cases, it's not intended for general use.  
At time of writing to boot in Ryujinx with latest devkitpro you need this Ryujinx branch: https://github.com/Ryujinx/Ryujinx/pull/555

Precompiled versions on releases.

What each thing does/tests  

# Template:  
Just a template to get an app running. Displays a white screen. For new apps you can copy this

# Geometry Shaders
Draws 4 vertical lines from single draw points call

# Uniforms
Draws a green triangle, colour passed with uniforms

# Constant Attributes
Triangle that oscillates letf to right, offset set by cosntant attribute

# Cube Maps
Displays a cube with a different texture for each face using cubemaps
