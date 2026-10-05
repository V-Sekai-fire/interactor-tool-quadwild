# interactor-tool-quadwild

A script that retopologizes a GLB mesh into quads through prebuilt QuadWild-BiMDF binaries.

## What it is for

It converts the input to OBJ, runs the quad remesher's preparation and quad-generation steps with a mechanical or organic setup, and exports the smoothed quad mesh back to GLB. The bundled binaries are Windows builds.

## Build and run

It needs the `trimesh` Python package and a `temporary` folder beside the script for intermediate files. The last argument is `mechanical` or `organic`.

```sh
python remesh.py <input.glb> <output.glb> organic
```

## Licence

The repository has no LICENSE file, so its licence is not stated. The bundled binaries keep their upstream licence.
