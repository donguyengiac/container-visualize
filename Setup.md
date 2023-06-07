# Setup

## Imagination
If you only need the imagination module, please install the following packages.
* [Pybullet](https://pybullet.org/wordpress/): the simulation engine used for the robot imagination. It can be installed by
    ```
    pip install pybullet
    ```
    
* scikit-learn: Principal Component Analysis (PCA) for the pouring imagination
  ```
  pip install scikit-learn
  ```

* [V-HACD](https://github.com/kmammou/v-hacd): convex decomposition of the mesh for pybullet simulation.
  ```
  git clone https://github.com/kmammou/v-hacd
  cd app 
  cmake -S . -B build -DCMAKE_BUILD_TYPE=Release 
  cmake --build build
  ```
* [Trimesh](https://github.com/mikedh/trimesh): mesh processing library. We use trimesh 3.9.1 in our expriment.
  ```
  pip install trimesh
  ```

* ffmpeg: saving the video of the imagination process.
  ```
  sudo apt install ffmpeg
  ```