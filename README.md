## This is not the original HTSL repository! For the original, made by BusterBrown1218 go to [this]() page!

Installation instructions:
0. Make sure ChatTriggers is installed correctly and up to date.
1. Download zip from releases
2. Extract zip to "./minecraft/config/ChatTriggers/modules/HTSL/
3. Launch game

To edit import files, do `/ct files` ingame, navigate into the HTSL folder, go into "imports" and you can create new importable files with the .htsl file extension.<br>
For auto-completion and syntax highlighting, use the [HTSL VSCode Extension](https://github.com/BusterBrown1218/htsl-plus).<br>
To see ingame commands do `/htsl` or `/htsl help`<br>

Huge thanks to Housing Editor and BusterBrown1218 for making this possible!

For HTSL support, you're more than welcomed in the [discord server](https://discord.gg/bptauV2BAA).

## What makes this different?
Hi, I (Meila), have gotten really into ChatTriggers module-making recently and got the idea to try to contribute to HTSL (my beloved) due to the long waiting times for updates.
Please note that I'm nowhere near as good of a programmer as BusterBrown, so updates will be small and less optimized than his.<br>
All my updates will expand upon suggested features from his discord, and features I've personally wanted myself :3<br>
You can find BusterBrown1218's repository [here](https://github.com/BusterBrown1218/HTSL), and the latest release of my version [here](https://github.com/MeilaLeinaLainen/HTSL/releases/latest).

Currently I've added/fixed `2` features which I explain below:

### Fixes:
- none yet

### Updates:
- **Import item to GUI slot.**<br>
This is a very small yet handy update that builds from the recent 'goto gui' addition to HTSL. The only thing changed is that if you add a string of the name to a item nbt json file, it will use put that item onto the slot. Example below:

```
goto gui "Test" 5 "stone" /* "stone" uses 'stone.json' in your imports folder */
chat "wasup world"
```

- **Detailed exported filenames.**<br>
Tiny update that makes the file you generate when you export actions to have it's own unique name to not only explain what it is, but also to stop overwriting the files if you want to export many things at once.