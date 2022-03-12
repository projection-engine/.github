# Projection engine

Motor gráfico construido do zero com WebGL2;

Suporte a algoritimos de ponta no quesito renderização e estruturado com padrão ECS (Entity, component, system).
Editor construido com electronJS e ReactJS com um editor de material poderoso e gerenciamento de arquivos integrado.

![Demo2](https://github.com/projection-engine/.github/blob/main/SCENE 2.png?raw=true)


<div style="display: flex;">
  <img src="https://github.com/projection-engine/.github/blob/main/Material v2.png?raw=true" alt="Editor material" style="width: 49%;"/>
  <img src="https://github.com/projection-engine/.github/blob/main/VS GI.png?raw=true" title="Light propagation volumes"  alt="demo" style="width: 49%;"/>
  <img src="https://github.com/projection-engine/.github/blob/main/BLEND.png?raw=true"  title="Material blend" alt="demo" style="width: 49%;"/>
  <img src="https://github.com/projection-engine/.github/blob/main/OMNI.png?raw=true"  title="Point light shadow maps" alt="demo" style="width: 49%;"/>
  <img src="https://github.com/projection-engine/.github/blob/main/True parallax.png?raw=true"  title="Parallax occlusion mapping" alt="demo" style="width: 49%;"/>
</div>

### Features

| Rendering                                                                    | UI                                              | Controles                              | Serialização | Desserialização                    | Outros                    |
|------------------------------------------------------------------------------|-------------------------------------------------|----------------------------------------|--------------|------------------------------------|---------------------------|
| FXAA                                                                         | Sistema de arquivos integrados com o navegador. | Mouse picking                          |              | Suporte a modelos .obj             | Simulação de gravidade    |
| Materiais e renderização Physically based + Parallax occlusion mapping       | Hierarquia de entidades                         | Transformações                         |              | Suporte a modelos .glTF (gltf 2.0) | Colisão com mesh esférica |
| IBL - Image based lighting                                                   | Elementos ajustaveis (tamanho)                  | Materiais                              |              |                                    |                           |
| Deferred shading                                                             | Temas                                           | Customização de tamanhos dos elementos |              |                                    |                           |
| Shadow maps - Suporte a 4 direções e baked shadow maps (em desenvolvimento). |                                                 | Preferências da UI                     |              |                                    |                           |
| Reflexões com cubemaps (em desenvolvimento)                                  |                                                 |                                        |              |                                    |                           |
