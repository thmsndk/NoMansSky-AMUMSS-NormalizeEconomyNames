This is a script that uses [AMUMSS](https://www.nexusmods.com/nomanssky/mods/957) to do what the [Normalize Economy Names](https://www.nexusmods.com/nomanssky/mods/657?tab=description) mod did

Removes unnecessary names from economy level, economy class and conflict levels. Does not alter gameplay just UI strings.

## Instructions
- Download & Extract [AMUMSS](https://www.nexusmods.com/nomanssky/mods/957)
- Place the desired `NEN_[LANGUAGE]_everything_AMUMSS.lua` file into the `ModScript` folder of [AMUMSS](https://www.nexusmods.com/nomanssky/mods/957)
- Run `BUILDMOD.bat` from the extracted [AMUMSS](https://www.nexusmods.com/nomanssky/mods/957) folder
- When asked
> ??? Would you like to COPY the created Mod PAKS to your game folder and DELETE [DISABLEMODS.TXT] [Y,N]?
- Press Y
- When asked if you want to check for mod conflicts, Press N
- Wait for ~5 minutes while the script is generating the mod
- The generated mod should now be present in your Mods folder and you can launch

## Other notes
- `REPORT.txt` will contain the result of running `BUILDMOD.bat` if you are interested in seeing what the .lua file changed
- `LANGUAGE/NMS_UPDATE3_[LANGUAGE].MBIN` is being modified.
- You can run `BUILDMOD.bat` with an empty `ModScript` folder and press `Y` when asked for checking conflicts to see if there are any conflicts between your currently installed mods.