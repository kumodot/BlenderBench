# MS Blender Add-ons Repository

This is my first Blender Add-ons repository.

I am a Senior 3D Artist with over 30 years of experience, and I started learning Blender in 2025 as a sidekick tool for my daily work — mainly for modeling, UVing, and 3D printing support.

As an advanced 3ds Max user, my add-ons are focused on replicating and adapting some of my personal workflows from other DCCs, aiming for speed, simplicity, and consistency.

All my Add-ons use the prefix **MS** (Marcelo Souza) for easier organization and recognition.

---

## 🧩 Available Add-ons

### [MS_3DPrintAid](./MS_3DPrintAid)

A helper tool for preparing Blender scenes for 3D printing.  
It sets the scene scale to millimeters, adjusts viewport grid to 1cm, adds a “safe build plate” visualization, corner labels, and includes a quick STL export cycling function.
<img width="1553" height="859" alt="image" src="https://github.com/user-attachments/assets/f29ee773-fc69-44da-9b1c-410090221ca4" />

  >>> The Export button will export the selected object as an STL file using the following naming sequence:
- 3dpart_bld_01.stl
- 3dpart_bld_02.stl
- 3dpart_bld_03.stl
      The files are saved in the root of your D:\ drive.

If you want to change the naming pattern or the save location, you can modify the Python code manually before installing the Blender Add-on.

The files will always overwrite themselves following this cycle. So, after exporting 3dpart_bld_03.stl, the next export will return to 3dpart_bld_01.stl, and so on. These are intended as temporary files, so if you wish to keep them, simply move or rename them after export.

### [MS_ColorAid](./MS_ColorAid)
<img width="892" height="753" alt="image" src="https://github.com/user-attachments/assets/92dc0021-b575-48fb-9d2f-9ec62c2f7e50" />

A utility to manage and preview object colors in the viewport for fast visual organization — ideal for modeling and layout workflows.
<img width="812" height="582" alt="image" src="https://github.com/user-attachments/assets/150d9ea1-cd2d-42f4-820f-6fe10c34b3a5" />

### [MS_PivotAid](./MS_PivotAid)
A small but powerful tool to align, center, or transfer object pivots quickly, mimicking some of the 3ds Max pivot controls.

---

## 🧰 Installation

1. Download the `.zip` of any add-on folder.  
2. In Blender: **Edit > Preferences > Add-ons > Install...**  
3. Choose the `.zip` and enable the Add-on.  

---

## 🧠 Notes

These add-ons are created mainly for personal use and learning purposes, but feel free to test them, suggest improvements, or report issues.  
I will update and polish them over time as I integrate Blender more into my daily workflow.

---

© 2025 Marcelo Souza – [@msouza3d](https://www.instagram.com/msouza3d/)
