# Projection engine

Projection engine is a free and open-source 3D graphics engine and editor.

#### [Follow the development here](https://github.com/orgs/projection-engine/projects/11/views/1)

---

<table>
    <tr>
        <th>
           <img src="https://github.com/projection-engine/editor/blob/next/showcase-images/img.png"/> 
        </th>
        <th>
          <img src="https://github.com/projection-engine/.github/blob/main/SSGI%20+%20SSAO.png?raw=true"/>  
        </th>
    </tr>
</table>
<small><a href="https://github.com/Vinc3r/cornellBox">Cornell Box by Vinc3r</a></small>
 
---

## Repositories

### [Engine core](https://github.com/projection-engine/engine)
  Renderer base structure
### [Editor](https://github.com/projection-engine/editor)
  Editor UI and app
  
## Milestones

- [x] **Fast and structured forward renderer**
- [x] **"Immediate" mode node editor**
- [x] **New lens effects**
    - [x] Motion blur
    - [x] Depth of field
- [x] **Dedicated transparency pass with access to opaque geometry information**
- [x] SSR with roughness based blur and normal influence
- [x] **New shading models**
    - [x] Sheen, clear-coat, anisotropic, isotropic, unlit
- [x] **Screen-space decals**
- [x] **Screen-space shadows for any light type**
- [x] More lights: now up to 310 lights can be integrated in a scene
- [x] Lighting improvements and early contribution discard for improved 
- [x] **Project selection without a separate app (HUB)**
- [x] Icons and lines for more editor information while working on a scene
- [x] Distance culling and screen-door effects
- [x] New grid rendering system
- [x] Orthographic projection
- [x] **New rotation gizmo renderer**
- [x] New debug shading methods: Lighting complexity, roughness/metallic/ao/albedo, random colors, 

## Future features

- [ ] Immediate mode UI editor (currently using static HTML and CSS)
- [ ] Node-based coding (blueprint like)
- [ ] Project templates
- [ ] Wireframe view 
- [ ] Detachable windows for shader-editor view and others
- [ ] Improved shadows (addition of spotlight shadows, filtering and other improvements)

## License

Projection Engine is licensed under the GNU General Public License, Version 3.
Some files may have other compatible licenses.

[For more information.](https://www.gnu.org/licenses/gpl-3.0.html)
