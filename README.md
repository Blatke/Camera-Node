# Camera-Node
This is a mod for adding a camera and a spotlight in the scene in Studio and controlling them.

![AI_2023-12-01-00-38-03-701](https://github.com/user-attachments/assets/f5893bf8-5170-4dd1-a963-24f47d777e97)

## How to Use
Please download the .zip file for the latest version on the [Release page](https://github.com/Blatke/Camera-Node/releases), and uncompress it. There are two files included:
1. A mod file, needs to drag and drop it into your **mods** folder.
2. A scene card file in format of .png, needs to put it into your **UserData\Studio\scene** folder

Please check the demonstration video for further introduction.
1. https://youtu.be/wkXY1RcD4lA
2. https://youtu.be/73CrEvw1lg8

## Basic Requirements
1. NodeConstraints the plugin (https://www.patreon.com/posts/hs-kk-ai-hs2-1-2-40763065) installed in Studio;
2. This mod installed in Studio;
3. Import the scene card into your scene instead of directly adding the items of this mod.

## Troubleshooting

Q: It doesn't work in the scene.

A: With ensuring that the 3 requirements listed on the thread above are all met, the reason could be in:

1. There is no character existing in the scene. There has to be at least one chara in the scene to activate NodeConstraints the plugin. So, just **add any one chara** to let it work.
2. The FK function of any objects in this mod's folder, especially the Aim sphere, is enabled on Anim tab. Active FK node will disturb NodeConstraints as well as the relationships among objects in this mod. So be sure that **their FKs are all disabled**.
![d6c45d7c7038de3241c6a16d6f8cb437_image_ex=66af48a2 is=66adf722 hm=65f33e1249100dca641e094f4024b3bc0d45c816cfe85bc98033986e53b95877](https://github.com/user-attachments/assets/b604b3e4-f1b2-451e-bdc8-33e43887de7f)
