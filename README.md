```text
███████╗██╗      ██████╗
██╔════╝██║     ██╔════╝
███████╗██║     ██║  ███╗
╚════██║██║     ██║   ██║
███████║███████╗╚██████╔╝
╚══════╝╚══════╝ ╚═════╝
```

<img width="1912" height="1439" alt="image" src="https://github.com/user-attachments/assets/b8c4df2c-72cd-4e4e-93f4-c7643d68c967" />

**WARNING: THIS BUILD CURRENTLY HAS A REGRESSION CAUSING IT TO LOCK UP DURING INTRO ON NAOMI HARDWARE**

**THE FOUR ADDED UPPER CHARACTERS DO NOT HAVE FINAL LINKED ASSETS, E.G., AFTER BATTLE QUOTES, PORTRAITS, ETC. THOSE HAVE BEEN IMPLEMENTED BUT ARE STILL BEING LINKED**

**How to use the patcher**

1. Open **SFA3_UPPER_Patcher_R73.exe** on 64-bit Windows.
2. Click **select your rom files** and choose your unmodified **sfz3ugd ROM ZIP and CHD**. A zipped CHD or matching stock DAT is also supported.
3. Click **select output folder**.
4. Click **patch** and wait for the progress bar to finish.
5. When **done** appears, your selected folder contains **SFZ3U26_R73.dat**.

Your original files remain unchanged. Everything needed for patching is built into the executable.

**What we changed from vanilla Street Fighter Zero 3 Upper**

**Characters and gameplay**

- Added **Eagle, Maki, Yun, and Ingrid**, using recovered Alpha 3 MAX/CFC2 character behavior, animations, voices, and effects.
- Added **Ingrid’s joint introduction with Blanka**.
- Corrected **Yun’s walking animation** and an intro-selection bug that could lock up his match on Charlie’s stage.
- Replaced **T. Hawk’s backward-walk artwork** with his Sega Saturn animation, preserving movement speed, timing, and collision behavior.
- Added **landing crouch cancel for aerial normals** by holding Down as the character lands.
- Fixed **Ken and Evil Ryu incorrectly treating the four newcomers as Ryu** during special introductions, including Ken’s pre-match soft-lock.

**Graphics and presentation**

- Multilingual / Region
- Integrated the **PSP/MAX opening sequence**, with corrections to scrolling colors, name effects, and retained native artwork.
- Corrected imported sprite palettes, flipped artwork, and animation references.
- Repaired **Evil Ryu’s corrupted victory portrait allocation**.
- Added **384×224 gameplay rendering**, scaled to a **640×480, 4:3 output**.
- Kept **“LOADING GAME NOW…” at 640×480**, then switched to the gameplay rendering resolution.
- Added a **DEBUG filter toggle**: hold either player’s Start for approximately three seconds, use Left/Right to change filtering, then release and press Start to close.
- Set the build back to the **USA region**.

**Performance, controls, and sound**

- Renders in SFA3 native resolution of 384 x 224 w/bilinear option to reduce (nearest).
- Revised **input/JVS timing**. Recorded emulator checks measured a two-frame path—approximately **33.33 ms**—rather than a verified physical controller-to-screen figure.
- Reworked rendering synchronization to address recurring slowdown in tested scenes.
- Removed a configured **PowerVR memory overlap** associated with the hardware flicker investigation.
- Reorganized audio caches and loading buffers to prevent memory collisions.
- Integrated and adjusted the newcomers’ audio, repaired announcer-buffer conflicts, and corrected **Vega’s music-loading boundary**.

**What’s changed in R73**

- Added **Eagle, Maki, Yun, and Ingrid** to the NAOMI game.
- Replaced **T. Hawk’s backward walk** with his Sega Saturn animation.
- Fixed **Ken’s incorrect special intro** against the four added characters, which could prevent the match from starting.
- Fixed **Evil Ryu’s incorrect Ryu-specific intro** against those characters.
- Retained the **USA region**, existing input/latency patches, and display updates.

**Remaining issues**

- **Maki:** Certain moves have been reported to make her fly or disappear off-screen. This remains under investigation.
- Earlier **Zangief V-ISM slowdown on hardware report** still needs confirmation against the current build.
