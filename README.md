# Iterated-Closest-Point ICP
Point-to-point ICP and Point-to-plane ICP

## References

The point-to-plane ICP algorithm used in this project is based on the following paper:
"Linear Least-Squares Optimization for Point-to-Plane ICP Surface Registration" [here](https://www.cs.unc.edu/techreports/04-004.pdf)

## Required Libraries

This project requires the following Python libraries:

- `numpy`: For numerical operations and array handling.
- `matplotlib`: For creating static, interactive, and animated visualizations in Python.
- `trimesh`: For loading and using triangular meshes.
- `scikit-learn`: Specifically, `KDTree` for efficient queries of the nearest neighbors.

## Supported File Formats

This project supports all mesh file formats that can be read by the **trimesh** library. For example, it can handle files in the following formats:

- `.stl` - Stereolithography files used for 3D printing
- `.ply` - Polygon file format
- `.obj` - A standard 3D model file format

### Viewing Exported Files

This code can export files in `.obj` format, which you can open and view in 3D model viewers such as **Meshlab**, **Blender**, or others. These tools offer powerful visualization and analysis features that can help you better understand and present 3D models.
