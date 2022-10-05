---
layout: project
type: project
image: images/compute_shader.gif
# title: Compute Shader
permalink: projects/compute_shader
# All dates must be YYYY-MM-DD format!
# date: 2015-12-15
# labels:
#   - Blender
#   - Python
# summary: A responsive web application for travel planning that my team developed in ICS 415.
---

<div class="ui embed" data-source="vimeo" data-id="-" ></div>

## COMPUTE SHADER

### About the project
TEXT TEXT TEXT

***

### Base functionality
<!--
<ins>Functionality is quite simple:</ins> Link all meshes that you want to export as a one object under an *export_node*. You can do it either in 3d viewport or in *Scene Collection* panel, name your exported object (name of your FBX file), search export path and hit export button. -->
TEXT TEXT TEXT

<div class="ui huge rounded image">
  <img class="ui image" src="{{ site.baseurl }}/images/-.jpg">
</div>


TEXT TEXT TEXT

<!-- *Name:* Name of FBX file<br>
*Path:* Where FBX file is going to be saved<br>
*isStatic:* Custom property<br>
*Export to FBX:* Button that exports meshes lined under this export node<br>
*Create a new export node:* When a mesh is selected in 3D viewport or in Scene Collection panel and thius button pressed, it creates a new empty export node in a position of this mesh.

<ins>Colliders:</ins> If user wants to export also collider objects together with the mesh they can do so by naming collider objects with specified suffixes: *boxcollider, capsulecollider, spherecollider, _coll*.

<ins>Flags:</ins> Additionally you can set *isStatic* boolean. This boolean sets a custom property to all objects under your *export_node* to *static*. When your object is imported to Unity3D this custom property is read and all objects with it are flagged by Unity3D editor as *Static*.

Static flag in Unity3D editor:
BatchingStatic, ContributeGI, ContributeGI, OccludeeStatic, OccluderStatic, ReflectionProbeStatic

Although FBX exporter is not responsible for seting any in-editor flags. `AssetPostprocessor.cs` is responsible for it: -->

<!--
```csharp
private void OnPostprocessGameObjectWithUserProperties(GameObject go, string[] propNames, System.Object[] values) {
    string metaKeyStatic = "isStatic";
    for (int i = 0; i < propNames.Length; i++) {
        if (System.String.Equals(propNames[i], metaKeyStatic) && (int)values[i] == 1) {
            GameObjectUtility.SetStaticEditorFlags(go, flags);
        }
    }
}
``` -->

***

Link to repository: [GitHub Link](http://www.asdasdsadas.com).

***