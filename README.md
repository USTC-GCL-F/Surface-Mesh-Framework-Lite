# Framework for surface mesh processing (Lite Version)

The program is used to load meshes and render using OpenGL. **This Lite version dose not have interactive features such as picking vertex and dargging vertex.**

## External Libraries

* [Eigen](http://eigen.tuxfamily.org/)
* [OpenMesh](https://www.openmesh.org/), Recommended version: the latest 8.1(at Oct. 2020)
* [Qt](https://www.qt.io/), Recommended version: 5.13.0

## Usage

```
git clone https://github.com/USTC-GCL/SurfaceFrameworkLite
cd SurfaceFrameworkLite
```

Edit lines 7-9 of CmakeLists.txt to set the values of **EIGEN_PATH**,**OPENMESH_PATH** and **OPENMESH_LIB_PATH**
```
mkdir build && cd build
cmake -A x64 ..
```

Open **SurfaceFrameworkLite.sln**, select **SrufaceFrameworkLite** as launch project, and run.

## Supported File Formats

.obj .off .ply .stl