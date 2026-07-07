This is a Reffect content pack. In order to use this you'll have to download Reffect (and therefore, Nexus) first. Please follow their setup instructions here: https://github.com/Zerthox/gw2-reffect

# Description

A Guild Wars 1 stylized UI for Guild Wars 2. It's set up in a homogenized layout for all classes, but you may duplicate it and customize it to your liking.

# Examples

A video to see the pack in action:

[![YouTube](https://github.com/user-attachments/assets/8759fb4a-6f4b-4f10-a379-30fa2e5e6938)](https://www.youtube.com/watch?v=qS4F2lmV3_A)

Examples of the default layout:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/55feb6e6-764b-495a-8d41-bd9eb2647768" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b30ba935-987f-4cd2-8309-39bfe8fa51d6" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f57e666a-75d8-493d-8eb0-a5134d2c20b7" />

Evoker (with Specialized Elements):

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1569f748-f359-464f-9109-96febe08c697" />



# How to use

Download "Venny GW1.zip" into your reffect root folder and extract. It should add the necessary files to the icons and packs subfolders. An additional Settings file is provided for style that's also recommended to download. More details below.

<img width="652" height="141" alt="image" src="https://github.com/user-attachments/assets/1d2c3445-ed6e-4644-8dae-dd2f987661a7" />

If you have GW2 open, restart it to let Reffect reloadd the pack.

Once the pack is installed, you'll have to **set the interface size that matches your current in-game interface size choice by Right clicking "Interface Normal" > Resize**:

<img width="640" height="275" alt="image" src="https://github.com/user-attachments/assets/94487424-91f8-4341-8d01-68e51d88080c" />
<img width="862" height="217" alt="image" src="https://github.com/user-attachments/assets/10c59814-9028-435f-bda5-ad0d6f86cbda" />

As listed, the sizes you should use are:

- Small: 90%
- Normal: 100% (Default, don't resize)
- Large: 110%
- Larger: 120%


By default, all the interfaces have the original layout. If you want to customize it, it's recommended you **duplicate** the group (by right-clicking). That way, you can keep the original as a reference while editing.
Most elements are grouped logically in a hierarchy. 

<img width="918" height="296" alt="image" src="https://github.com/user-attachments/assets/b2e53606-e43f-45b8-b2bd-9760907893d1" />

Navigate the hierarchy to find the element or group you wanna move and place it wherever you want it to display. Reminder that positions are inherited, so if you move a parent, all children will move with it, keeping their own positions as offsets.

Weapon and utility hotbars are shared between all classes. Same for health and endurance bars. 
Each class has their own profession mechanic bars.

# Keybinds

A corner to display keybinds has been added as well. However, Reffect cannot tell which key is bound to each slot yet, so if you want to have accurate text, you will have to edit the corresponding key in the text element. The default keybinds have been set for these elements:

<img width="721" height="195" alt="image" src="https://github.com/user-attachments/assets/57bb44f2-8738-463e-be60-efe6ae340723" />

You can find the editable text by navigating the hierarchy into the element you want to change, and you'll find it under Keybind > Key text. For example, to change the Weapon skill 2's keybind:

<img width="966" height="716" alt="image" src="https://github.com/user-attachments/assets/17a6486b-b95f-4613-aa7d-3f6c36211290" />


# Buffs

A few options have been added for buffs. By default, boons and conditions have been replaced with (mostly aesthetically) matching skill icons from the first game as well. The full conversion table is:

<img width="634" height="197" alt="image" src="https://github.com/user-attachments/assets/de57a313-7637-48e2-af29-fd59dec1389d" />

However, an option to have GW2 regular buffs is also available.

<img width="268" height="409" alt="image" src="https://github.com/user-attachments/assets/919799a7-ddc6-4cd5-9c63-62deb7744131" />

Additionally, a handpicked selection of combat buffs that need to be visible but aren't as clear to translate to a bar setup have been added to the buffs list.

**Note:** the list with the combat buffs will appear quite longer as ALL possible buffs will appear at the same time, despite no class being able to have them all at once.


# FAQ

### **- Game icons look like this**

<img width="872" height="195" alt="image" src="https://github.com/user-attachments/assets/45fdffbf-3fc4-442c-b2a3-19c2ea2efd67" />

The setting to **reuse game icons is required** for this pack to function:

<img width="364" height="145" alt="image" src="https://github.com/user-attachments/assets/babef52d-c5ab-40d3-9881-925959b32d0e" />

### **- The default UI is showing up behind the pack**

You can change your HUD settings as such:

<img width="666" height="440" alt="image" src="https://github.com/user-attachments/assets/b8c4bda0-7cc2-49f4-ba9c-d7848ac11c02" />

The important ones to note:
- Skill bar (never show)
- Mount skill bar (never show)
- Temporarily show UI for notifications (Disabled to prevent the UI popping in when gliding)
- Use "Show ally names" keybind to display the UI so you can change your skills. You will probably need to set up a keybind in reffect to hide overlays. Alternatively, you can use the Build tab of the hero panel.

# Known Issues

- Merged Soulbeast and Unleashed Pet Untamed have their pet portraits unavailable so they have been replaced with something else or removed. Soulbeast skills will be moved to the profession bar instead of the pet panel, as most of the gameplay is intended to be done while merged.

Unleashed Pet

<img width="246" height="118" alt="image" src="https://github.com/user-attachments/assets/a56d2042-6c03-40a0-87b8-04df6e01cae9" />

Soulbeast

<img width="736" height="266" alt="image" src="https://github.com/user-attachments/assets/f0a1fb56-5906-45a3-bfcc-cd6d0d442c1e" />

<img width="715" height="189" alt="image" src="https://github.com/user-attachments/assets/a822fcb2-6d64-493e-84da-d49431458c90" />

# Settings

A settings file is provided to style buffs to look as close to ingame as possible, with pretty stack markers and white duration bars instead of the default neon green. This is optional but highly recommended. It's only separate for users who may have customized their settings for other packs already.

<img width="123" height="55" alt="image" src="https://github.com/user-attachments/assets/9d546406-b656-45fd-9723-4d0209d8a5ee" />
