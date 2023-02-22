# picom-o8dither
Ordered dithering shader for picom.

## Why?
I just love that oldschool orderred dithering and I heard that it was pretty fast
as a fragment shader, so I decided to leard OpenGL because of it, lol.
And then I found out that picom has support for user-defined shaders and some people have
made pretty incredible stuff with them, so I just had to do it!

## Usage
`picom --window-shader-fg fadeDither.glsl`

## Demo
Screenshots were taken using 6-level quantization.
You may want to set a higher color count to make it less noticable, or the opposite.

### o8dither.glsl
<p align="center"><img src="true_sxiv.png"></p>
<p align="center"><img src="true_q3a.png"></p>

### fakeDither.glsl
<p align="center"><img src="fake_sxiv.png"></p>
<p align="center"><img src="fake_q3a.png"></p>

This video demonstrates two shaders with fading:

### halfFakeDither+Fade.glsl fadeDither4x2.glsl
<p align="center"><video controls><source src="fade_demo.mkv"></source></video></p>
