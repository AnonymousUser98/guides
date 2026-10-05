---
title: Recommended Emulators
permalink: /emulators/
---

## Nintendo Entertainment System (NES)
The best NES emulator is [Mesen](mesen.ca). It's cycle-accurate and has lots of features.


## Nintendo 64

### For Casual Play
See if there is a PC port for the game you want to play. If you need to use an emulator, use [RMG (Rosalie's Mupen GUI)](https://github.com/Rosalie241/RMG).

If your computer can handle it, use the **ParaLLEl-RSP** and **ParaLLEl-RDP** plugins. Otherwise, use **GlideN64** and HLE.

### For High Accuracy
Use [ares](https://ares-emu.net/), but make sure your computer can handle it.\
You can also use [Bizhawk](https://tasvideos.org/Bizhawk) with the _Ares64_ core.

### For TASing
Use [Bizhawk](https://tasvideos.org/Bizhawk). Set the preferred core for N64 to _Ares64_. If your computer can't handle it, switch to _Mupen64plus_ with the _Angrylion_ video plugin and the _cxd4_ RSP plugin. If your computer still can't handle it, switch to GlideN64 and HLE (but keep in mind it won't be as accurate).

### For Using STROOP (with SM64)
There are 2 options for this.

#### [Mupen64 Repack](https://mupen64.com/)
If you're using it for advanced TASing, this is what you should use. It's used by the SM64 TASing and ABC community, and it has advanced LUA scripting features.

#### [Bizhawk](https://tasvideos.org/Bizhawk)
For advanced testing and experimenting with STROOP (or glitchhunting), use Bizhawk to get high-accuracy emulation. Keep in mind that you'll need to use the original STROOP because the FramePerfection refactor doesn't work with Bizhawk.

To use STROOP with Bizhawk's Ares64 core (which is more accurate), you'll need to remove the text `offsetDll="mupen64plus.dll" ramStart="0x6A1C0"` from the Bizhawk line in `Config.xml`.

### For Playing SM64 ROM Hacks
You should use Parallel Launcher. It will automatically configure the emulator settings for the specific ROM hack that you're playing, and it has easy RetroAcheivements integration through RetroArch.
