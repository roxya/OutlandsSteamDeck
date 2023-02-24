# Outlands on Steam Deck

## Intro

This is a guide for running UO Outlands on Steam Deck using Bottles. Feel free to contact me on Discord (**roxya#2313**) if you have issues or questions. 

- You won't have to use the command line
- You won't have to make changes to the operating system or disable Steam's read-only filesystem
- It should continue to work after Steam Deck OS updates
- It will work in game mode
- You'll get 60 FPS without any stuttering

## Guide

- [Installing required software](https://github.com/roxya/OutlandsSteamDeck/blob/main/README.md#installing-required-software)
- [Setting permissions on the home directory](https://github.com/roxya/OutlandsSteamDeck/blob/main/README.md#setting-permissions-on-the-home-directory)
- [Bottles preferences](https://github.com/roxya/OutlandsSteamDeck/blob/main/README.md#bottles-preferences)
- [Preparing the bottle](https://github.com/roxya/OutlandsSteamDeck/blob/main/README.md#preparing-the-bottle)
- [Installing Outlands](https://github.com/roxya/OutlandsSteamDeck/blob/main/README.md#installing-outlands)
- [Adding the shortcut](https://github.com/roxya/OutlandsSteamDeck/blob/main/README.md#adding-the-shortcut)
- [Adding Outlands to Game Mode](https://github.com/roxya/OutlandsSteamDeck/blob/main/README.md#adding-outlands-to-game-mode)
- [Running in Game Mode](https://github.com/roxya/OutlandsSteamDeck/blob/main/README.md#game-mode)

## Download Outlands

Start by downloading the Outlands launcher/installer from https://uooutlands.com/connecting/

## Installing required software

Go into Desktop Mode by holding the power button and select Switch to Desktop

![image](https://user-images.githubusercontent.com/7057924/211849244-f92af11b-bda4-4639-a85c-94ab85477f25.png)

Open the Discover app and search for and install these three applications

- Bottles
- Flatseal
- Boilr

![image](https://user-images.githubusercontent.com/7057924/211850076-d99ebd5d-1c7d-448d-8601-73acf9f6a80a.png)

## Setting permissions on the home directory

In order to install Outlands to Home instead of the bottle itself, we need to allow Bottles to access the Home directory. The advantage of installing to Home is that it's easy to access if you need to edit/delete files, copy or backup profiles, etc. It also allows us to start over with the bottle if anything goes wrong, without the launcher having to download the Outlands game files again.

Open the Flatseal app, select Bottles from the left side. Scroll down on the right side until you get to the Filesystem section and enable "All user files"

![image](https://user-images.githubusercontent.com/7057924/211853689-64a66650-3b27-4784-becc-d5ef0221ef70.png)

## Bottles preferences

Open the bottles app and enter the Preferences window.

![image](https://user-images.githubusercontent.com/7057924/218490923-e9cadd87-27c0-43f9-aa7d-9b928584d083.png)

On the Runners tab, click Soda and download `Soda 7.0-8` if not already downloaded.

![image](https://user-images.githubusercontent.com/7057924/218491662-b1aa6f9b-790e-4b7e-a129-2dc3eecc91ed.png)


## Preparing the bottle

At the Bottles home screen, press the + in the top-left corner to create a new bottle. Choose a name, make sure Gaming is selected, and press the blue Create button.

![image](https://user-images.githubusercontent.com/7057924/211854750-38213ce9-19fe-44cb-b992-e147db1205f6.png)

Once the bottle has been created, click on it to open it. Go into Settings and change the runner to `Soda 7.0-8`

![image](https://user-images.githubusercontent.com/7057924/221146564-fc62c963-791c-4850-8441-f3dd8a898499.png)

Scroll down to the Compatibility section. Click on `DLL Overrides`, add `tabtip.exe` as a new override, and set it to Disabled.

![image](https://user-images.githubusercontent.com/7057924/211856264-d40b8b4b-0339-4763-bd8b-d6164ae023ce.png)

![image](https://user-images.githubusercontent.com/7057924/213929329-512f2f5f-dad9-432f-9977-74b3538520d3.png)

Click the arrow in the top-left corner to return to the main page for the bottle.

## Installing Outlands

Press the blue Run Executable button and select the Outlands.exe file downloaded earlier

![image](https://user-images.githubusercontent.com/7057924/221147083-e53981d9-8288-4496-9c10-c8096e2e3c31.png)

![image](https://user-images.githubusercontent.com/7057924/211857617-173cc745-77f4-417e-84f3-f194c0fe5de2.png)

The Outlands launcher will appear, asking you to install it to ``C:\Program Files (x86)\Ultima Online Outlands``. Press the button to the right side of the path to choose a different directory.

![image](https://user-images.githubusercontent.com/7057924/211858454-8aad938d-f9e1-4efb-9815-55540f2ca261.png)

On the left side of the Select Folder window, browse to My Computer, Z:\, home, and then click on the deck folder

![image](https://user-images.githubusercontent.com/7057924/211858828-59af8fca-f46e-4e36-9241-a4b294e38520.png)

Press Open. You should see the new install path of ``Z:\home\deck\Ultima Online Outlands`` displayed.

![image](https://user-images.githubusercontent.com/7057924/211859007-8606ea61-a744-471f-967f-8208112cbb30.png)

Press OK to install. When it finishes and you can see the Play Now button, close the launcher.

## Adding the shortcut

On the main page for the bottle, click the Add Shortcuts button and browse to ``Outlands.exe`` in Home/Ultima Online Outlands (**not** the Outlands.exe in your Downloads folder) and press Add.

![image](https://user-images.githubusercontent.com/7057924/221147552-11ecc9f7-112d-4e0d-93f7-fba9731e2eb3.png)

![image](https://user-images.githubusercontent.com/7057924/211859967-26d32220-d681-4f40-ac8d-da960e5670a4.png)

You should see Outlands appear in the Programs list. If not, exit Bottles and go back in. If it's still not there, try using Add Shortcuts again.

Press the Play icon to ensure Outlands works in Desktop mode. If it doesn't, it's unlikely that it'll work in Game Mode, so now is the time to start trying to fix it.

![image](https://user-images.githubusercontent.com/7057924/211860464-d56643cd-eaa7-4c72-97e7-7ca2f199287e.png)

You may see some graphical glitches. They should not be present when playing in Game Mode so let's ignore them.

![image](https://user-images.githubusercontent.com/7057924/211861076-e2ebc1aa-3a71-4d1c-9429-fedf6ad13aa6.png)

## Adding Outlands to Game Mode

To play Outlands outside of Desktop Mode, you need to add it to Steam as a non-steam game. Bottles has a built-in feature for this, but unfortunately it doesn't work well, at least not for Outlands. Instead, we'll do it using a tool called Boilr.

Open the Boilr app we installed at the start.

![image](https://user-images.githubusercontent.com/7057924/211860846-ab678360-b8f8-4045-93bb-fedf19aa8689.png)

By default Boilr wants to add everything it can find to Steam. If you only want to add Outlands and have many items from other launchers in the list, it can be quite the chore to uncheck them all. Therefore, you may want to go into Boilr's settings and uncheck all of the ``Import from`` options, except for ``Import from Bottles`` which must be checked.

![image](https://user-images.githubusercontent.com/7057924/211861684-dce5603e-ac46-4317-b798-5a5efa1cef30.png)

Now go back to the Import Games screen and make sure Outlands is selected. Then press the image in the bottom left of the screen to import it to Steam.

![image](https://user-images.githubusercontent.com/7057924/211862186-f569799d-d6bc-410d-8410-2b9423ceb340.png)

A message will appear confirming that it has imported the selected games.

## Running in Game mode

Use the desktop icon to Return to Gaming Mode. You should find Outlands in your library under the Non-steam games category. Simply run it and it should open. You'll need to use the mouse (hold the Steam button and use the right trackpad or stick) to press Play Now.

### When ClassicUO launches, you may find that the Razor window is taking up the whole screen.

Press the Steam button and you should see the ``Switch Windows`` section showing Razor and ClassicUO. Select ClassicUO and you should see the login screen.

#### If window switching doesn't appear to work

Exit the game and go into Steam Deck settings (Steam button, Settings). In the System page, use the ``Enable Developer Mode`` option. You should now be able to use window switching to switch between ClassicUO and Razor.

### If ClassicUO has black borders on the left and right sides

Go into ClassicUO's options, Video, and enable Borderless Window.
