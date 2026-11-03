```text
███████╗██╗      ██████╗
██╔════╝██║     ██╔════╝
███████╗██║     ██║  ███╗
╚════██║██║     ██║   ██║
███████║███████╗╚██████╔╝
╚══════╝╚══════╝ ╚═════╝
```

<img width="1912" height="1439" alt="image" src="https://github.com/user-attachments/assets/b8c4df2c-72cd-4e4e-93f4-c7643d68c967" />

<img width="640" height="480" alt="C06_VMU_640x480" src="https://github.com/user-attachments/assets/b788e9f4-1cc0-4b55-b32c-3e197dce7316" />

<img width="640" height="480" alt="C06_Insert_VMU" src="https://github.com/user-attachments/assets/2bfb92b8-b294-4d30-8d90-4844438b0297" />

<img width="640" height="480" alt="download (1)" src="https://github.com/user-attachments/assets/56f36c3f-3c7e-45b5-ac56-3083f379059f" />

**THIS BUILD IS NOW COMPATIBLE WITH NAOMI HARDWARE. BIG, BIG THANKS TO LIAM S. FOR BEING INSTRUMENTAL IN TESTING**

**THE FOUR ADDED UPPER CHARACTERS AND GAME ENGINE HAVE BEEN FULLY IMPLEMENTED AND ADUITED**

~ *two dialogue scenes were omitted due to memory constraints (although I'm still trying to make it work)*:

   - Ingrid/Blanka: Blanka waits for an Ingrid auxiliary actor that the port never starts, causing the introduction to lock.
   - Maki/Rolento: Maki expects a PSP-specific Rolento counterpart routine missing from native NAOMI Rolento.

*IF YOU ENCOUNTER ANY BUGS, PLEASE REPORT THEM HERE*

SFA3 UPPER RC3 PATCHER — Windows 10/11 x64

1. Extract the ZIP and run SFA3_UPPER_Patcher.exe.
2. Select sfz3ugd.zip and gdl-0002.chd together, or drag both into the window.
   If they are in different folders, use the separate CHD button.
   Alternatively choose Stock DAT / BIN and select your original stock image.
3. Select your PSP Alpha 3 MAX game file (any regional version).
4. Choose an output folder, then click Create BIN.

Output: SFA3U_C11.bin

Your original files remain unchanged. Everything needed for patching is built into the executable.

**Known issues**

**What we changed from vanilla Street Fighter Zero 3 Upper**

Street Fighter Alpha 3 Upper — NAOMI RC3 Update:
------
Added features
- Added four playable fighters: Eagle, Maki, Yun, and Ingrid.
- Added character-specific opening stories, rival encounters, dialogue, endings, victory quotes, and ranking artwork for the four fighters.
- Restored crouch cancel as an Operator Menu option.
- Added a VMU ON/OFF setting that stays active during gameplay.

Fixes and polish
- Fixed the delayed start of Gen’s stage music.
- Fixed a crash during CPU-controlled Yun fights.
- Fixed Yun’s 1P and 2P banner spacing on the character select screen.
- Fixed two missing lines in Ingrid’s post-battle dialogue with Ryu and restored her pre-battle dialogue with M. Bison.
- Restored the missing lower-body artwork in Ingrid’s ending.
- Fixed pre-fight lockups in Ingrid vs. Blanka and Maki vs. Rolento by using their regular introductions.
- Adjusted the title-screen prompts and credit line to clear the Capcom copyright text.

Builds and patchers
- Available in 384×224 240p and 640×480 480p. Both builds include the shared gameplay and character fixes.
- The 240p build uses native filtering and has a simplified Operator Menu.
- Both Windows patchers work offline and accept a supported NAOMI ROM ZIP + CHD pair or a single DAT/BIN.
