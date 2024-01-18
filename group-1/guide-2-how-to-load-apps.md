# Guide 2: How to Load Apps

Loading apps is a simple but tedious process if you don't know how to do it.

{% hint style="info" %}
You will need to download the Hitfel 5 Game Station to properly load apps.

You can download the addon [here](https://github.com/ProID-Corporation/Hitfel-5/releases/tag/V2.2).

It is also recommeneded to use [TurboWarp](https://turbowarp.org/) for this.
{% endhint %}

## Part 1 - Getting your app assets

1. Pick one of the projects from the [explore ](https://scratch.mit.edu/explore/projects/all)tab. (Pick one with less assets, to conserve time)
2. Press See Inside.
3. Copy all assets (backdrops, costumes, sounds, and sprites) into the backpack.
4. You're done!

## Part 2 - Setting up Game Station

1. Open your copy of the Hitfel 5 Game Station.
2. Press See Inside.
3. Go to the Variables section.
4. Set the "verloaded" variable to the Version of the app. (EX: V1, 1.0)
5. Set the "nameloaded" variable to the name of the app.
6. Make an empty sprite and name it AppInfo.
7. Add the following code: **"when Green Flag clicked" "add (join Name = (nameloaded var)) to LoadedRequirements" "add (join Name = (verloaded var)) to LoadedRequirements"**
8. You're done!

## Part 3 - Importing

1. Import all assets from the Backpack into the Game Station.
2. Replace all "when Green Flag clicked" blocks with "when I receive startloaded".
3. Also add this code: **"when I receive kill load" "hide" "stop all sounds" "stop other scripts in sprite" "stop this script"**
4. You're done!

## Part 4 - Transfer to Hitfel 5

1. Make sure you have completely followed all steps in Part 3 and Part 2.
2. You can test the app by pressing the RUN APP button in the Game Station.
3. Import all modified assets into the Backpack. (You can delete the old, unmodified ones.)
4. Open your copy of the Hitfel 5. You must be using Version 2.2 or higher. To check your system version, go to the Main Menu and look at the bottom right. Optionally, you can also check with [Aurora](../home-menu/aurora.md) or [System Settings](../home-menu/system-settings.md).
5. You can download the latest version of the Hitfel 5, [here](https://github.com/ProID-Corporation/Hitfel-5/releases).
6. Make sure you have [fully installed the system](../installation.md).
7. Press See Inside and import all the assets from your backpack including AppInfo.
8. Restart your Hitfel 5 system.
9. Boot up your Hitfel 5 system.
10. Press Hitfel 5.
11. Open the Loaded app.
12. The app should now officially load your app.
13. You're done!
