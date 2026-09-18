# 🏎️ PDM Loader & Interior Fix (FiveM Enhanced)

![FiveM Ready](https://img.shields.io/badge/FiveM-Enhanced_Ready-orange?style=for-the-badge&logo=fivem)
![Lua](https://img.shields.io/badge/Language-Lua-blue?style=for-the-badge&logo=lua)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Hey everyone! 👋 

Since upgrading to **FiveM Enhanced** (latest gamebuilds), many server owners noticed that `bob74_ipl` is no longer fully compatible, causing issues like missing floors, flickering textures, or blue occlusion walls at the **Premium Deluxe Motorsport (PDM)** dealership.

I created this lightweight, standalone resource to fix the PDM interior natively, clear out ambient GTA traffic/ped spawns, and allow easy custom prop placement.

---

### ✨ Features

* 🚀 **FiveM Enhanced Compatible**: Uses direct native IPL requests (`v_carshowroom`, `shutter_open`, `shr_int`) without external dependencies.
* ⚡ **0.00ms Performance**: Extremely lightweight client scripts with zero impact on resmon.
* 🛑 **No Default Traffic/NPCs**: Automatically suppresses ambient vehicle generators and scenario peds inside the showroom.
* 🪑 **Built-in Prop Spawner**: Includes an easy-to-use script (`props.lua`) to add furniture or display cars with automatic distance cleanup.
* ⚙️ **Standalone**: Works on QBCore, ESX, vRP, or Custom Frameworks.

---

### 📦 Installation

1. Download the latest release from **GitHub**.
2. Drag and drop the `pdm_enhanced` folder into your `resources` directory.
3. Add `ensure pdm_enhanced` to your `server.cfg`.
4. Restart your server!

---

### 🔗 Links & Download

* 📂 **GitHub Repository:** [https://github.com/zapprojectrp/pdm_enhanced]
* 📄 **License:** MIT

---

> *Feel free to leave feedback, report bugs, or submit pull requests on GitHub!*
