## Demo Url
 
[Demo](http://leone.computing.dcu.ie/~bivolm2/imgui8/)

## Possible Causes
 - `draw_cmd.TextureId` is null, `gl.genTextures` is something I'm certain is needed for this value not to be null.
 - `draw_cmd.drawElements()` isn't doing what it's meant to do due to something that needs done by tinyGL.



### ImGuiDear_JS_TinyGL

This code is experimental, but the goal is:
 - to get TinyGL and ImGui to Work toghether
 - to display onto canvas context 2d (same thing)

