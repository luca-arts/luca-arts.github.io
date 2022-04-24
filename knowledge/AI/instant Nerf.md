instant nerf should be able to make a 3D mesh from some images.

[instant-ngp link](https://github.com/NVlabs/instant-ngp/)

## installation

### colmap

you need colmap installed **with** CUDA support: [installation link](https://colmap.github.io/install.html#pre-built-binaries). 
*I'm on linux so I have to compile from source as noted to have CUDA support.*

#### issues

1. On my ZBook Fury I noticed I got a `cc1plus` errorr while running `make -j` . This is probably due to having too much processes runnin
2. 
3. 
4. 
5. g in parallel. To test I went for `make -j4` .
6. I got an error at the end of make process,  something with an undefined reference to LIBTIFF. I had to deinstall libtiff via conda: `conda uninstall libtiff` .
7. 

### instant-ngp

#### issues

1. I had to install qt5-qmake (perhaps this was for colmap?): `sudo apt-get install qt5-qmake` 
2. 

