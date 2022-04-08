# NYU_VR_Projects
 VR projects as part of NYU's XR Development Course

# Week 12
Instructions : Download this repository containing a Unity package file. Import the package into a new project in Unity 2021.

Objectives :
- The maze includes at least four turns.
- The maze includes at least two dead ends.
- The environment objects are aligned to the grid.
- The player must use a grabbable object to progress further.
- A win state is activated upon entering the final section.
- The maze must be playable with the VR headset.
- The project must be on GitHub and marked public.

[Screen recording of maze playthrough.](https://www.loom.com/share/3b6a29f0ac794e7f80f7a0138263c8e9) (soundtrack is poorly recorded from Oculus headset)

[The maze was built with assets created by Kay Lousberg @KayLousberg.](https://twitter.com/KayLousberg) I have used these assets in other projects, and wanted to experiment with their performance in VR. The dungeon pack assets contain a number of scene building materials with only one side for better perforamce when rendering visuals.

See screenshots below for maze overview with requisite number of turns, dead ends, interactables, grid alignment via ProGrids, etc.

This project was challenging, as it was the first project I have constructed in VR. The project was built with XR Interaction Toolkit, Plugin Manager, and OpenXR for Oculus in Unity 2021. These build choices were made to reduce compatibility and functionality issues that arose when attempting to use earlier versions of those packages. While many of the key components are the same in a general sense, numerous details, features, and functionality have been altered since the creation of the project example. Furthermore, many of the core XR packages used in the example project were in a preview state. This project uses packages that are out of preview.

This maze project will be expanded in future projects to include animations and increasted interactivity, as well as fine-tuning the VR experience, bug fixes, etc.

Maze layout requirements :
![Maze_Layout_requirements](https://user-images.githubusercontent.com/73659857/162364298-3eee6c70-3068-4a12-9bdf-304b74e8ccba.jpg)
Interactive Keys and Doors :
![Interactive_Keys_Doors](https://user-images.githubusercontent.com/73659857/162364319-86612c10-a695-4d61-999b-60b6323ffa76.jpg)
Grab-Interactable Swords : 
![Grab_Interactable_Swords](https://user-images.githubusercontent.com/73659857/162364321-068e504c-3c63-4a42-9204-d7006cca0acc.jpg)
