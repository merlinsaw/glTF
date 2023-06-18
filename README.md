# glTF
useful Tools when creating content for the glTF and glb file format


## tools for blender

### shader_oppacity_blendmode
**Transparency in glTF and GLB files can present challenges** related to alpha channels, shader settings, and compatibility with different 3D applications and engines.
Therefore, it can be helpful to **change the shader of the material to "Opaque"** to avoid potential issues with transparency when working with glTF and GLB files.

The main function of the provided script in Blender is to recursively change the shader blend mode to 'OPAQUE' for all materials in the object hierarchy. Additionally, it helps in finding the RootNode object, creating a new collection, linking the RootNode object to the collection, and scaling the RootNode object.

## tools for maya
