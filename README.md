# TOC
- [TOC](#toc)
  - [List of notebooks](#list-of-notebooks)
    - [Blender](#blender)
  - [Tips](#tips)
      - [Symlink from Google Drive.](#symlink-from-google-drive)

## List of notebooks

### Blender
[![Open in colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/melMass/notebooks/blob/main/blender_render.ipynb)

This is a basic example on how to use blender inside of Colab.
With blender you can do a lot of different operations on a lot of data types.
The blender API is very good.
Some random use case:
- Batch converting/baking textures
- Batch converting 3D models
- GPU rendering
- Thumbnailing
- etc...

A very good example use case is [BlenderProc](https://github.com/DLR-RM/BlenderProc)

---

## Tips

#### Symlink from Google Drive.
When you use a private notebook (not a forked public one but one you create from scratch), you can automaticaly load Google Drive with the runtime. This is very useful for example to retain data accross sessions.
What I usually do in my private notebooks is creating a specific folder per notebook on my drive, for instance `MyDrive/notebook/01-first_notebook` that I then symlink for easy access
```python
!ln -sfn "/content/drive/MyDrive/notebook/01-first_notebook" "/content/01-first_notebook"
```
