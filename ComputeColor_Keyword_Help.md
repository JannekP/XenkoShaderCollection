# XenkoShaderCollection


Compute color:

        // http://en.wikipedia.org/wiki/Blend_modes#Dodge_and_burn
        // The Color Burn mode divides the inverted bottom layer by the top layer, and then inverts the result
         return float4(1.0f - BlendUtils.ColorDivide((1.0f - backColor.rgb), frontColor.rgb), 1.0f);

	BlendUtils.Equals(frontColor.rgb, 1.0f));

	BlendUtils.BasicBlend(backColor, frontColor, interColor);
	
	Global.Time

	streams.Position

# Inheritance

Texturing:

streams.TexCoord  -> Texture Coordinates(UVs)


Utilities:

contains fresnel and convertations


Transformation, PositionStream4:

Eye.xyz  -> Cameraposition
streams.PositionWS.xyz  -> World Position


MaterialSurfaceDiffuse:

streams.matDiffuse
streams.matColorBase


<bool TInvert> : MaterialSurfaceGlossinessMap<TInvert>:

streams.matGlossiness


NormalStream:

streams.meshNormalWS
streams.normalWS
streams.NdotL


ColorBase:

streams.Color


VelocityStream:

streams.velocity
streams.ShadingPosition


PositionStream4:

streams.DepthVS


# Functions

clamp()
dot()
frac()
lerp()
max()
min()
saturate()
mul()
sin()
cos()
abs()
...
https://docs.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl-intrinsic-functions




