# ComputeColor Cheatsheet


### Compute color:

        // http://en.wikipedia.org/wiki/Blend_modes#Dodge_and_burn
        // The Color Burn mode divides the inverted bottom layer by the top layer, and then inverts the result
         return float4(1.0f - BlendUtils.ColorDivide((1.0f - backColor.rgb), frontColor.rgb), 1.0f);

	BlendUtils.Equals(frontColor.rgb, 1.0f));

	BlendUtils.BasicBlend(backColor, frontColor, interColor);
	
	Global.Time

	streams.Position
	
	Math.PI
	
	

## Inheritance

**Texturing**

streams.TexCoord  -> Texture Coordinates(UVs)


**Utilities**

contains fresnel and convertations


**Transformation**

Eye.xyz  -> Cameraposition


**MaterialSurfaceDiffuse**

streams.matDiffuse
streams.matColorBase


**<bool TInvert> : MaterialSurfaceGlossinessMap<TInvert>**

streams.matGlossiness


**NormalStream**

streams.meshNormalWS
streams.normalWS
streams.NdotL


**ColorBase**

streams.Color


**VelocityStream**

streams.velocity
streams.ShadingPosition


**PositionStream4**

streams.PositionWS.xyz  -> World Position
streams.DepthVS


## Functions

**abs(x)**
Returns the absolute value of the specified value.

**acos(x)**
Returns the arccosine of the specified value.

**all(x)**
Determines if all components of the specified value are non-zero.

**ceil(x)**
Returns the smallest integer value that is greater than or equal to the specified value.

**clamp(x, min, max)**
Clamps the specified value to the specified minimum and maximum range.

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




