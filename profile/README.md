# Projection engine

The **Projection Engine** is a 3D graphics engine designed and written from ground up to be multi-platform and easy to use.

Multiple features are already implemented or on the way to the editor, here is a list of some of those features:

|                                                  Simple scene                                                  |                                                  Material editor                                                   |
|:--------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/projection-engine/.github/blob/main/SCENE 2.png?raw=true" alt="Editor material"/> | <img src="https://github.com/projection-engine/.github/blob/main/Material v2.png?raw=true" alt="Editor material"/> |

|                                    Parallax occlusion mapping                               |                            Light propagation volumes global illumination (dev)                             |
|:--------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------:|
|  <img src="https://github.com/projection-engine/.github/blob/main/True parallax.png?raw=true"  title="Parallax occlusion mapping" alt="demo"/> | <img src="https://github.com/projection-engine/.github/blob/main/EEE.png?raw=true" alt="Editor material"/> |

|                                    Directional and omnidirectional shadows                                     |                            Node-based Scripting                        |
|:--------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/projection-engine/.github/blob/main/OMNI.png?raw=true" alt="Editor material"/> | <img src="https://github.com/projection-engine/.github/blob/main/scripting.png?raw=true" alt="Editor material"/> |

### Viewport

- **Manipulation**: 
  - Transformation gizmos:
    - Rotation
    - Translation
    - Scaling
  - Entity picking
  - Hot keys
  - Multi select
  - Transformation for multiple entities
  - Individual manipulation grid for rotation, scaling and translation 
  - Hierarchical transformation
- **Visualization**
  - Rendering modes for debug and ease of use
  - Entity highlight
  - Icons
  - World grid

### Rendering
- **Post processing**
  - FXAA
  - Film grain
  - Chromatic aberration
  - Multi-step bloom
  - Lens distortion
- **Materials and PBR rendering**
  - Unlit
  - Forward and deferred renderers
  - Directional and omnidirectional shadows with PCF filtering
- **GI**
  - Light probes (under development)
  - Light propagation volumes (under development)
  - CubeMap specular reflections
- **Other**
  - SSAO with depth reconstruction for both forward a deferred shaded materials
  - Fully physically based pipeline with metallic workflow

### Editor
- **File system**
  - Folders and files management
  - Bookmarks 
  - Navigation shortcuts
  - Search
- **Scene structure**
  - Entity-component-system with hierarchical structure
  - Custom material uniforms editable via form
  - Folders and multi-select
  - Transformations and component attribute manipulation
- **Multi-tab system**
- **Shared GPU context for fast tab switching**
- **Parallel processing (IPC and workers)**
  - Project loading
  - glTF import
  - File system refreshes
  - Image processing
  
### Blueprints
- **Scripts**
  - Multiple nodes for custom scripts
  - Compiled down to native language
- **Groups**
  - Color customization
  - Label
- **Materials**
  - Custom material/shader creation with nodes
  - Multiple pre-crafted functions
  - Compiled down to glsl
  - Custom program generator
  - Multiple rendering methods.
- **Custom scripts written in JS**

### UI creation
> Under development
