# Projection engine

This is a solo, open-souce project of a full-on 3D graphics engine, intended to be used to create small to medium size
interactive desktop and web applications.

If you would like to contribute with this project, your feedback would be extremely appreciated.

## Download - [v5.8.1-alpha](https://github.com/projection-engine/editor/releases/tag/v5.8.0-alpha)
<table>
    <tr>
        <th>
          SSGI Before 
        </th>
        <th>
          SSGI After 
        </th>
    </tr>
    <tr>
        <th>
           <img src="https://raw.githubusercontent.com/projection-engine/.github/main/v5.8.0/SSGI-BEFORE.png"/> 
        </th>
        <th>
          <img src="https://raw.githubusercontent.com/projection-engine/.github/main/v5.8.0/SSGI-NOW.png"/>  
        </th>
    </tr>
  <tr>
        <th>
           SSGI ON 
        </th>
        <th>
           SSGI OFF 
        </th>
    </tr>
    <tr>
        <th>
           <img src="https://raw.githubusercontent.com/projection-engine/.github/main/v5.8.0/SSGI-ON.png"/> 
        </th>
        <th>
          <img src="https://raw.githubusercontent.com/projection-engine/.github/main/v5.8.0/SSGI-OFF.png"/>  
        </th>
    </tr>
</table>

## Follow the development

You can follow the project development via the following boards:

### [New features](https://github.com/orgs/projection-engine/projects/6)

New features coming to the engine in the near/medium distance future.

### [Bugs](https://github.com/orgs/projection-engine/projects/5)

Known bugs.

### [Improvements](https://github.com/orgs/projection-engine/projects/4)

Currently existing features with improvements coming to how they work.

## Currently under development (v10.0.0-alpha)
> Due to the scope of this update this will take more time than previous updates.

- New editor backend with [**Tauri**](https://github.com/tauri-apps/tauri)
    - Completely rewritten file system backend
    - New window management structure
    - new glTF loader (rust based)
    - Support for update via the editor UI itself
    - Move away from embedded window frame to native window frame
- Terrain system (pre-alpha)
    - Sculpting
    - Layered materials
    - Layer painting
    - New editor view
- Big rendering optimization
    - Depth pre-pass and Deferred pass will now work together
- PhysicsAPI
    - Access to AmmoJS physics instance
    - Terrain physics builder
- Infinite scroll changes
    - Integration with native svelte component for infinite-scroll
    - provides same behaviour as default scrolling but with element culling

## Repositories

### [Engine](https://github.com/projection-engine/engine)

Rendering stuff including editor tools.

### [Editor](https://github.com/projection-engine/editor)

Editor UI including **Svelte** frontend and the **Electron** backend.

## Screenshots

<table>
    <tr>
        <th>
            Scripting and debug
        </th>
        <th>
            UI creation
        </th>
    </tr>
    <tr>
        <td>
             <img src="https://raw.githubusercontent.com/projection-engine/.github/main/v5.1.0/UI-EXECUTION.png"/>      
        </td>
        <td>
            <img src="https://raw.githubusercontent.com/projection-engine/.github/main/v5.1.0/UI.png"/>                                                               
        </td>
    </tr>
    <tr>
        <th> 
            Gizmos
        </th>
        <th>
            glTF importer
        </th>
    </tr>
    <tr>
        <td>
            <img src="https://raw.githubusercontent.com/projection-engine/.github/main/v5.8.0/GIZMOS.png"/>  
        </td>
        <td>
           <img src="https://raw.githubusercontent.com/projection-engine/.github/main/v5.8.0/PBR.png"/>                                                 
        </td>
    </tr>
    <tr>
        <th> 
           SSGI  
        </th>
        <th>
           SSAO
        </th>
    </tr>
    <tr>
        <td>
            <img src="https://raw.githubusercontent.com/projection-engine/.github/main/v5.8.0/SSGI-NOW.png"/>
        </td>
        <td>
            <img src="https://raw.githubusercontent.com/projection-engine/.github/main/v5.8.0/SSAO.png"/>                                      
        </td>
    </tr>
</table>

### Licence

The Projection Engine and all its modules are licenced under an MIT licence.
