# Pytorch3d playground

## How to install Pytorch3D ?

Everything is explained in the [README](https://github.com/facebookresearch/pytorch3d/blob/master/INSTALL.md) of the pytorch3D lib.

As I have CUDA 10.1, which is an old version, I need to run this command : 
``̀ pip install torch==1.6.0+cu101 torchvision==0.7.0+cu101 -f https://download.pytorch.org/whl/torch_stable.html```

I wanted to build pytorch3d the easiest way so I sticked with an older version of torch : 1.6.0.

In order to install pytorch, you need to run :

``̀ pip install pytorch3d```

ATTENTION, as I was saying above, this works with pytorch 1.6.0 only.

## Learning

Learning [PyTorch3D](https://github.com/facebookresearch/pytorch3d) in order to work on a university project for mesh transformation.

### First step 

The first tutorial I made is based on the ["deform a source mesh to form a target mesh"](https://pytorch3d.org/tutorials/deform_source_mesh_to_target_mesh) tutorial.

From this, I learned how to load objects and meshes and how to modify them.

### Second step

The next thing I read about is [rendering texture](https://pytorch3d.org/tutorials/render_textured_meshes)

For mesh texturing there is several options : vertex textures, UV textures and face textures