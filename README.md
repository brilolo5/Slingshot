# Slingshot
Slingshot converts the Android version of **Rovio Classics: Angry Birds** into a game that runs on Windows.

## Installation
1. Get an APK of the Android version (x86_64 architecture) of Rovio Classics: Angry Birds. This could be acquired if you bought the game when it was available on the Google Play Store. Only tested on the latest version released, 1.3.1519.
2. Run `Slingshot.exe`.
3. Select the APK you previously extracted.
4. Download Unity 2021.3.42f1 and tick **Windows Build Support (IL2CPP)** under modules to install the appropriate Unity Windows player version; the tool will then load it automatically. Otherwise, guide the tool to the player if you have it separately.
5. The game will build automatically and will create a folder on the root folder of `Slingshot.exe`.

## Mod support
Melon Loader is installed by default and includes patches (`GamePatches.dll`) that apply proper mouse detection, as well as fixed bugs. Don't delete it unless you know what you're doing, the game won't get past the loading screen.

## Credits
* [Project Dream](https://gitlab.com/adokova1111/project-dream-release) by Beatz, a tool that inspired me to develop my own.
