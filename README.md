# Minecraft Tutorial Mod

This mod was created by following the the tutorial embedded below. More specifically [Fabric Modding Tutorial - Minecraft 1.21](https://www.youtube.com/playlist?list=PLKGarocXCE1H_HxOYihQMq0mlpqiUJj4L) by [Modding by Kaupenjoe](https://www.youtube.com/@ModdingByKaupenjoe).

The initial template was generated at https://fabricmc.net/develop/template/ and the mod code is the product of following the tutorial playlist.

## Progress

- [x] Getting Started (finished as of commit [a7288fb](https://github.com/MommyHedgehog/tutorialmod/commit/a7288fb86e803b29021a6e632a6625b46930adec))
- [ ] Custom Items
- [ ] Custom Blocks
- [ ] Item Groups
- [ ] Custom Recipes and Loot Tables
- [ ] Custom Advanced Item
- [ ] Custom Advanced Block
- [ ] Custom Food and Fuel
- [ ] Custom Tooltips
- [ ] Custom Tags
- [ ] Data Generation Setup
- [ ] Non-Block Blocks
- [ ] Blockstates Explained
- [ ] Data Components Explained

## Development

I develop using VSCode. To develop this mod on VSCode you want to ensure you have JDK 21 installed on your computer and the [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) installed in your VSCode extensions. 

You will also need to have the $JAVA_HOME environmental variable set. This can be done using `echo export "JAVA_HOME=\$(/usr/libexec/java_home -v 21)" >> ~/.bash_profile` on Mac OSX. After running this command you need to close VSCode + your terminal and re-open them for your bash profile to take effect.

1. Clone this repo and open in VSCode
2. On opening VSCode should start importing the Gradle project (if it does not start after about 30 seconds, open the build.gradle file).
3. Once that is done you can code to your hearts content :heart:
4. To test your mod, go to "Gradle" (elephant) in the left sidebar which will open a pane describing your Gradle Projects including this one. Under Tasks > fabric you will see "runClient" --click either the debug or the play icon to the left of this task and Minecraft should start!
