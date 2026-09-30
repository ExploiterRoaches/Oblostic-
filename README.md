**On PC (Windows/Mac/Linux)**

1. Install **JDK 21** (Adoptium Temurin) and **Gradle 8.12+**.
2. Unzip `oblostic-fabric-1.21.4.zip`, open a terminal in the `oblostic` folder, and run `gradle build`.
3. Your mod is `build/libs/oblostic-1.0.0.jar` (ignore the `-sources` jar).
4. Install the **Fabric installer** from fabricmc.net. Pick Minecraft **1.21.4** and click Install.
5. Download **Fabric API for 1.21.4** from Modrinth. Optionally grab **Sodium**, **Lithium**, and **Iris** too, for FPS.
6. Put all the jars in `.minecraft/mods`. On Windows, press Win+R and type `%appdata%\.minecraft\mods`.
7. Open the Minecraft Launcher, choose the **fabric-loader-1.21.4** profile, and play.
8. In game, press **Right Shift** for the menu and hold **C** to zoom.

**On mobile**

Oblostic only works with **Minecraft Java Edition**. It won't run on the normal Bedrock mobile app.

1. **Build the jar on a PC first** (steps 1-3 above). Building on a phone isn't practical. If you have no PC, upload the project to GitHub and let a GitHub Actions Gradle build make the jar.
2. **Android:** install **ZalithLauncher** or **PojavLauncher** and sign in with your Microsoft account that owns Java Edition.
3. In the launcher, set the Java runtime to **21**, then install **Fabric 1.21.4**.
4. Copy the Oblostic jar, Fabric API, and Sodium into the game's `mods` folder, using the launcher's "open mods folder" option or a file manager.
5. Launch the game. Use the on-screen controls to open the Oblostic menu, since Right Shift is hard to reach on touch.
6. **iPhone/iPad:** Java mods are very limited. Your best bet is a PC.

**Tips**
- On mobile, turn off some HUD modules, because phones are slower.
- If the game crashes, check that Fabric API and the Minecraft version (1.21.4) match.
- Keystrokes and CPS are most useful with a keyboard and mouse, so on mobile they matter less.

Want help setting up the GitHub Actions build so you can get the jar without a PC?
