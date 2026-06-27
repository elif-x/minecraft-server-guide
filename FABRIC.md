Using the provided nest egg,
1. Determine what version of Minecraft you'll be using
2. Find the appropriate Java version for that version (8, 17, 21, etc.)
3. Delete all the Java versions under Configuration/Docker Images except the one corresponding to your desired version (i.e. java 21|ghcr.io/ptero-eggs/yolks:java_21)
4. Under Variables, change Minecraft Version, Fabric Version and Fabric Loader Version to your desired values
  - If using something like Prism Launcher, you can find these under Version/Fabric Loader and Mods/Fabric API, respectively.
