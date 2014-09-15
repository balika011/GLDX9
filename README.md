DirectX9 -> OpenGL translation layer.

Originally was taken directly from the DOTA2 source tree.

Supports:
 - Limited subset of Direct3D 9.0c
 - Bytecode-level HLSL -> GLSL translator
 - Some SM3 support: Multiple Render Targets, no Vertex Texture Fetch

This most likely won't build by itself and is provided as-is and completely
unsupported. Feel free to use it for your reference, incorporate it into your
projects or send us modifications.

Be wary that some parts are hardcoded to match Source Engine behavior.
(CentroidMaskFromName and ShadowDepthSamplerMaskFromName in dxabstract.cpp)

Please refer to the LICENSE file for more information.
