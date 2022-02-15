## Poiyomi 8 LTCGI Adapter Module by voxie

### Project Requirements
* Unity 2019.4.31f1
* Latest VRCSDK Worlds 
* UdonSharp by Merlin [https://github.com/vrchat-community/UdonSharp](https://github.com/vrchat-community/UdonSharp)
* LTCGI by _pi [https://github.com/PiMaker/ltcgi](https://github.com/PiMaker/ltcgi)
* Poiyomi 8 Alpha [https://poiyomi.com](https://poiyomi.com)

### Installation
Import into your project all project requirements in the order listed.   
Drop the Assets/ folder from this repository into your Project folder.
In the toolbar, navigate to Poi->Tools->Modular Shader Generator  
Select the checkbox for "Poiyomi ProLTCGI Adapter" and set the Destination to "Assets\_PoiyomiShaders\Shaders"  
You can now use the shader named ".poiyomi/V8.0/ProLTCGIADapter" for your materials.

### Shader Properties
* LTCGI Enabled - enables/disables the lighting contribution from LTCGI for this material
* Intensity Multiplier - scales the intensity of the lighting contribution from LTCGI
* Roughness Multiplier - scales the perceived roughness of the reflection of the lighting contribution from LTCGI

### Example Scene
Open the scene "Poi8LTCGIAdapterExample" in "Assets/Poi8LTCGIAdapter/Scenes" AFTER following the installation steps. Each sphere in the scene has an example material.

### Known Limitations
Lighting from LTCGI only works on meshes already in the world.
Each material created needs a tag specified in the String Tag Map to be updated in editor. This must be done manually for now. See below for instructions.

To set a material tag:
* Select your material in the Project window
* Change the inspector mode to Debug 
* Add a slot to the String Tag Map
* In the new slot, set First to "LTCGI" and Second to "ALWAYS"

If you need to see an example, each example material has this tag already set.

### Links
My Discord [https://voxie3d.com](https://voxie3d.com)  
I make avatars, sold on Gumroad and Booth:  
[https://app.gumroad.com/voxieavatars](https://app.gumroad.com/voxieavatars)  
[https://voxie.booth.pm](https://voxie.booth.pm)  


### License
MIT
