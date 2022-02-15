## Poiyomi 8 LTCGI Adapter Module
#### by voxie 

### Project Requirements
* Latest VRCSDK Worlds 
* UdonSharp by Merlin [https://github.com/vrchat-community/UdonSharp](https://github.com/vrchat-community/UdonSharp)
* LTCGI by _pi [https://github.com/PiMaker/ltcgi](https://github.com/PiMaker/ltcgi)
* Poiyomi 8 Alpha [https://poiyomi.com](https://poiyomi.com)

### Installation
Import into your project all project requirements in the order listed.   
Import the Poi8LTCGIAdapterModule UnityPackage into your project.  
In the toolbar, navigate to Poi->Tools->Modular Shader Generator  
Select the checkbox for "Poiyomi ProLTCGI Adapter" and set the Destination to "Assets\_PoiyomiShaders\Shaders"  
You can now use the shader named ".poiyomi/V8.0/ProLTCGIADapter" for your materials.

### Shader Properties
* LTCGI Enabled - enables/disables the lighting contribution from LTCGI for this material
* Intensity Multiplier - scales the intensity of the lighting contribution from LTCGI
* Roughness Multiplier - scales the perceived roughness of the reflection of the lighting contribution from LTCGI

### Example Scene
Open the scene "Poi8LTCGIAdapterExample" in "Assets/Poi8LTCGIAdapter/Scenes" AFTER following the installation steps. Each sphere in the scene has an example material.

### Links
My Discord [https://voxie3d.com](https://voxie3d.com)
My avatars for sale [https://app.gumroad.com/voxieavatars](https://app.gumroad.com/voxieavatars) and Booth [https://voxie.booth.pm](https://voxie.booth.pm)


### License
MIT
