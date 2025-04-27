# Minecraft Tutorial Mod

This mod was created by following the the tutorial embedded below. More specifically "Fabric Modding Tutorial - Minecraft 1.21" by [Modding by Kaupenjoe](https://www.youtube.com/@ModdingByKaupenjoe).

The initial template was generated at https://fabricmc.net/develop/template/ and the mod code is the product of following the tutorial.

[![Fabric Modding Tutorial - Minecraft 1.21](https://img.youtube.com/vi/oU8-qV-ZtUY/0.jpg)](https://www.youtube.com/watch?v=oU8-qV-ZtUY&list=PLKGarocXCE1H_HxOYihQMq0mlpqiUJj4L)

## Development

I develop using VSCode. To develop this mod on VSCode you want to ensure you have JDK 21 installed on your computer and the [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) installed in your VSCode extensions.

1. Clone this repo and open in VSCode
2. On opening VSCode should start importing the Gradle project (if it does not start after about 30 seconds, open the build.gradle file).
3. Once that is done you can code to your hearts content :heart:
4. To test your mod, go to "Gradle" (elephant) in the left sidebar which will open a pane describing your Gradle Projects including this one. Under Tasks > fabric you will see "runClient" --click either the debug or the play icon to the left of this task and Minecraft should start!
