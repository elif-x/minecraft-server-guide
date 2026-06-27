Using the provided nest egg,
1. Determine what version of Minecraft you'll be using
2. Find the appropriate Java version for that version (8, 17, 21, etc.)
3. Delete all the Java versions under Configuration/Docker Images except the one corresponding to your desired version (i.e. java 21|ghcr.io/ptero-eggs/yolks:java_21)
4. Under Variables, change Minecraft Version to your desired version. You **do not** need to change the Fabric and Fabric Loader versions, probably. Leave them as latest unless you run into issues.
