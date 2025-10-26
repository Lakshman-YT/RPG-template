# 🏹 Godot 3D RPG Player Controller Template
---

## 📋 Quick Highlights

| Field           | Details                |
|-----------------|------------------------|
| 🎮 Name         | **RPG-Template**       |
| 📌 Version      | **1.0**                |
| 🔀 Variants     | **Base & Advanced**    |
| 📅 Updated Date | **September 9, 2025**  |

---

🎉 **LIMITED-TIME SALE**

- 🛠️ **Base Controller** — $15  
  💳 [Buy Base on Itch.io](https://gw-tuts.itch.io/rpg-template-bow-controller)  
  🎓 **New to this controller? Start with the Lite YouTube Course:**  
  ▶️ [Watch Free Base Controller Playlist](https://www.youtube.com/playlist?list=PLXOuFjRwH6NgIKFFaksHL6eyqwgailMFv)  
  💡 Includes a beginner-friendly walkthrough of the Base Controller setup, bow mechanics, and movement fundamentals.  
  🔹 Note: Lite course **does not include GUI or advanced systems**. Source code not downloadable.

- ⚔️ **Advanced Controller** — $29  
  💳 [Buy Advanced on Itch.io](https://gw-tuts.itch.io/adv-rpg-template-bow-arrow-controller)  
  🔥 Unlocks advanced HUD, VFX pack, audio, and upcoming exclusive updates. Perfect if you want the full system with all features and future additions.

> ⚠️ **Important Note:**  
> The controller you buy contains only **logic and setup**. Animations must be downloaded separately.  
> A dedicated **YouTube tutorial (English)** is included in the download zip to guide you through setup.  
> The controller is provided **as-is, as shown in the demos**.


Future updates will add advanced VFX and audio packs for the Advanced Controller (no fixed timeline).  

---

## 🎮 Download & Try the Demo

### 🎯 Choose your version and platform:

#### 🛠️ Base Controller Demo
- 🪟 [Download for Windows 64-bit](https://www.jioaicloud.com/l/?u=cFYEj4ybOa6U-qqagg-2J7WQts04gEJF-TZoCiuCP7bCU-OPiBLvhJ5xEg2eAOG5doB)  
- 🐧 [Download for Linux 64-bit](https://www.jioaicloud.com/l/?u=oxvCJ6cmKjGjGUuOc-jTU3d22vXSX2nmYxIEZRee4g9hfWmKbwfhX89HwSj8tb8CNL3)  

#### ⚔️ Advanced Controller Demo
- 🪟 [Download for Windows 64-bit](https://www.jioaicloud.com/l/?u=c1HypF32BvEDHwzpxRQxkBZT9l2XaFeNurzC-TenwrEtw17su_ZUs-OIEvP4sfSFhIb)  
- 🐧 [Download for Linux 64-bit](https://www.jioaicloud.com/l/?u=5Nf450QQQTgEMhBfh7rehEegHvYBnZVjituiJVu-4mJo3YFhxj5VY6QLpT9Td8Dmb3F)  

🍏 **macOS?** No native build yet...  
_"Use a virtual machine, or break free and join the penguins 🐧"_

## ⚠️ Note
The download files are hosted externally due to GitHub’s **200 MB file size limit** (and Git LFS bandwidth restrictions).  
This ensures **faster upload and download speeds**.  

📺 Development log is available on the project’s **YouTube channel**.  

⚠️ **Trust Note:**  
All `.exe` and Linux builds are **officially compiled by me (Lakshman-YT)**.  
They are **100% safe, free from any virus or malware**, and can be downloaded without hesitation. ✅

📺 **Watch Gameplay on YouTube**  
👉 [Watch Demo Video](https://youtu.be/mSowhJhtzpk)

🎓 **Free Lite Course (YouTube Playlist)**  
A beginner-friendly series walking you through the **Base Controller** setup step by step.  
Perfect for learning fundamentals before diving into advanced systems.  
▶️ [Watch the Full Playlist Here](https://www.youtube.com/playlist?list=PLXOuFjRwH6NgIKFFaksHL6eyqwgailMFv)

---

## 🖼️ Gameplay Screenshots

![Gameplay 1](https://raw.githubusercontent.com/Lakshman-YT/RPG-template/refs/heads/main/images/1.webp)  
![Gameplay 2](https://raw.githubusercontent.com/Lakshman-YT/RPG-template/refs/heads/main/images/2.webp)  
![Gameplay 3](https://raw.githubusercontent.com/Lakshman-YT/RPG-template/refs/heads/main/images/3.webp)  
![Gameplay 4](https://raw.githubusercontent.com/Lakshman-YT/RPG-template/refs/heads/main/images/4.webp)  
![Gameplay 5](https://raw.githubusercontent.com/Lakshman-YT/RPG-template/refs/heads/main/images/5.webp)

---

## ✨ Features

### 🎯 Bow & Arrow Combat System
- Light and heavy arrow attacks with aim mode  
- Time-slow ability while aiming  
- Smooth equip and unequip transitions  

### 🤺 State-Based Character Controller
- Crouch, jump, fall, block, dodge, punch, and kick  
- Responsive and fluid transitions between actions  
- Jumping possible during active combat state  

### 🧠 Realistic Reactions
- Heavy and light hit reactions from all directions (front/back/left/right)  
- Natural head movement during idle/walk  

### 🔁 Root Motion Integration
- Uses root motion for accurate movement (not basic sliding)  
- Clean and smooth animation blending  

### 📊 Custom HUD
- Beautiful circular HUD for stamina and time-slow display  
- Crosshair updates dynamically for light/heavy attacks  

### 🧱 Test Environment
- Dummies for arrow test, hitbox testing, ragdolls  
- Kickable/punchable boxes for physical interaction  

---

## 📌 NEW in this Update

### ⚙️ Animation Improvements
- Added **sudden stop animations** for active state  
- Fixed **diagonal leg blending** across all states  
- Added **idle animation logic** for all states  
- Fixed **looping stutter** (seen in slow motion during animation loops)  
- Fixed **leg blending** from aim → active state  
- Improved **crouch → active transitions** (no more glitches on repeated triggers)  
- Smoothed **equip/unequip bow transitions** on repeated triggers  

### 💀 Player States
- Added **Death state** with various animations and revival logic  

### 🩸 UI & Gameplay
- Added **Health bar and GUI elements**  
- Fixed **glitches during movement switching** and other minor issues  

---

## 🚧 Future Upgrades / Known Issues
- 🔊 Add audio effects for actions and combat  
- 💥 Add visual effects (VFX) for bow and arrow  
- Jump hitbox not recognised  

---

## 🧰 Technical Highlights
- 🧩 **Organized Codebase** with clean state machine logic  
- 🛠️ **Plugins Used**  
  - [`PhantomCamera`](https://github.com/ramokz/phantom-camera) — dynamic third-person camera  
  - [`Limbo`](https://github.com/limbonaut/limboai) — animation and movement tools  
- 🏹 **Optimized Animations** (bow & arrow packs modularized and ready)  

---

## 🛡️ License & Usage Terms

- ✅ You **can use** this template in **personal** or **commercial** game projects.  
- ❌ You **cannot redistribute** the template (as-is or modified), or share the **source code**, publicly or privately.  
- 🧑‍🤝‍🧑 If you plan to use this in a **team or company project (6+ members)**, please get permission by contacting:  
  📧 **Lakshman001@outlook.com**  

🔐 **All rights reserved.**  
📄 Full details available in the [TERMS.md](TERMS.md)  

---

## 🎓 Learn the Basics (Lite Course)
Want to understand how everything fits together before diving into the full template?  
Watch the **Lite Version YouTube Course**, covering setup, bow mechanics, and movement fundamentals:  
🎥 [Watch on YouTube](https://www.youtube.com/playlist?list=PLXOuFjRwH6NgIKFFaksHL6eyqwgailMFv)

---

## 🎨 Credits & Assets

- The player model (dummy mannequin) is licensed under **CC0** and downloaded from [Quaternius](https://quaternius.com).  
- The **bow model, arrow model, and textures** were created by **Lakshman-YT** and are included in the template.  

---

## 🐞 Found an Issue? Report It!

1. Go to the **[Issues tab](https://github.com/Lakshman-YT/RPG-template/issues)**.  
2. Click **“New Issue”**.  
3. Provide details (steps, expected vs actual, screenshots if possible).  

> Clear issues = faster fixes! 🔧

---

Thanks for checking it out!  
Happy developing — and may your arrows always hit the mark 🏹  
