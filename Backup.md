# Home Menu Theming

### Console keys needed!
You need your console keys dumped for this. Check [lockpick](https://github.com/shchmue/Lockpick) out if you haven't dumped your keys already!
	
### Windows only!
This guide requires windows apps to work.

### Switch theme example:
![ExampleSwitchTheme](https://raw.githubusercontent.com/suchmememanyskill/SwitchThemeGuide/master/ThemingExample.jpg)


	

## What you need 

- The latest release of [NXThemeInstaller and Switch Theme Injector v3.4](https://github.com/exelix11/SwitchThemeInjector/releases)
	- You need both the `NXThemeInstaller.nro` and `ReleaseV3.4.zip`
- Your `prod.keys` keyset file
	
## Dumping required files

1. Unzip `ReleaseV3.4.zip` to somewhere on your pc's drive.
2. Place `NXThemeInstaller.nro` in the switch folder on your sd card.
3. Boot switch CFW, launch the homebrew launcher and launch `NXThemes`.
4. Navigate to `Dump NCA` and press + to dump the home nca.
5. Turn your switch off and put the sd card back into your pc.
6. Launch the `SwitchThemes.exe` app from the `ReleaseV3.4.zip`, navigate to `extract NCA`. Select your keyset file from your switch (`prod.keys`) and the `themes/systemData` folder on your sd card.
7. All .szs files required for theming are now located in `themes/systemData` on your sd card. Copy them to your pc if you want to make themes manually later on.


## Making a theme

Note:
Only the lockscreen and homescreen can be individually themed on <=5.1. The settings, news and all software home menu parts will have the same background as the homescreen.

1. Open up the `SwitchThemes.exe` app. Navigate to `NXTheme Builder`.
2. Select a Home menu part, A 720P image and a Layout patch. Click on `Build NXTheme` after selecting your home menu part, image and layout patch.
3. Fill out the details in the window that pops up. After filling out this window and clicking ok, you will get asked where to save the NXTheme file. Save this file in the `themes` folder on the sd card
4. Repeat these steps for every home menu part of the switch you want to modify.
	
## Installing a theme

1. Boot switch CFW, launch the homebrew launcher and launch `NXThemes`.
2. Navigate to `Themes`, Your theme file('s) should be listed here. You can install them one by one.
3. Reboot your switch to see the changes.

## Sharing a theme
The `(name).nxtheme` files are completely legal to share! On the flipside, the .szs files are **illegal** to share, as they contain coprighted content. 

## Test downloads
[Test Lockscreen](https://cdn.discordapp.com/attachments/450631843583229954/524649804144574464/TrianglesLock.nxtheme)
[Test Homescreen](https://cdn.discordapp.com/attachments/450631843583229954/524649801241985054/SunlightWavesHome.nxtheme)
