Protocol for preparing images for import into Sketchnote 3D

# Open the model in Metashape
## Reorient the object
* The model initially appears in top view
* *Rotate Object* displays a wheel that allows the model to be moved while the axes (windows bottom right)remain fixed: align Z upward, Y backward, and X to the left
* Then display the side of the model : 

```Model > Predefined views > Left```
> This displays the model's RIGHT side; this is normal.

* Use *Rotate Object* again to align the object with the axes

* Repeat in Front and Back views

## Adjust the bounding box
``` 
Model > Predefined views > Top
Region > Rotate region to local frame
```
* Resize the region to enclose the object

## Export
```File > Export > Export model as GLB file```

> Make sure that Export texture and Vertex normals are checked, otherwise the texture will not display automatically.
# Open the model in Blender
Unfortunately metashape cannot export export compressed glb files. 

``` Fichier > Importer > GLTF```

In *Collection de la Scène* (windows right upper corner) delete the cube (right click)

```Fichier > Exporter GLTF```
> Under *Données* check *Compression*