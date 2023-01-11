# OutlandsSteamDeck
This is a guide for running UO Outlands on Steam Deck using Bottles.

- You won't have to use the command line
- You won't have to disable Steam's read-only filesystem
- It should continue to work after Steam Deck OS updates
- It will work in game mode
- You'll get 60 FPS without any stuttering

# Download Outlands

Start by downloading the Outlands launcher/installer from https://uooutlands.com/connecting/

## Installing required software

Go into Desktop Mode by holding the power button and select Switch to Desktop

![image](https://user-images.githubusercontent.com/7057924/211849244-f92af11b-bda4-4639-a85c-94ab85477f25.png)

Open the Discover app and install

- Bottles
- Flatseal
- Boilr

![image](https://user-images.githubusercontent.com/7057924/211850076-d99ebd5d-1c7d-448d-8601-73acf9f6a80a.png)

## Setting permissions on the home directory

In order to install Outlands to Home instead of the bottle itself, we need to allow Bottles to access the Home directory. The advantage of installing to Home is that it's easy to access if you need to edit/delete files, copy or backup profiles, etc.

Open the Flatseal app, select Bottles from the left side. Scroll down on the right side until you get to the Filesystem section and enable "All user files"

![image](https://user-images.githubusercontent.com/7057924/211853689-64a66650-3b27-4784-becc-d5ef0221ef70.png)

## Preparing the bottle

Open the Bottles app and press the + in the top-left corner to create a new bottle. Choose a name, make sure Gaming is selected, and press the blue Create button.

![image](https://user-images.githubusercontent.com/7057924/211854750-38213ce9-19fe-44cb-b992-e147db1205f6.png)

Once the bottle has been created, click on it to open it. Go into Settings and switch the runner from ``soda`` to ``sys-wine``. It will take a short while.

![image](https://user-images.githubusercontent.com/7057924/211856264-d40b8b4b-0339-4763-bd8b-d6164ae023ce.png)

![image](https://user-images.githubusercontent.com/7057924/211856318-8187509c-c903-4e9d-94a4-af087ba1f767.png)

Click the arrow in the top-left corner to return to the main page for the bottle, and then go into Dependencies.

![image](https://user-images.githubusercontent.com/7057924/211856473-83f06fff-1008-48a2-b9ab-71ed8e300bef.png)

Click the download icon next to each of these dependencies

- dx3d11
- dotnet48 (will take longer than the others, wait for it)
- gdiplus
- mono

![image](https://user-images.githubusercontent.com/7057924/211856760-00a398b1-e433-4b7c-bb72-02f29cab8760.png)

Click the arrow in the top-left corner to return to the main page for the bottle

## Installing Outlands

Press the blue Run Executable button and select the Outlands.exe file downloaded earlier

![image](https://user-images.githubusercontent.com/7057924/211857479-c84bc2ee-413b-4660-9a10-d4f8c5c13323.png)

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

![image](https://user-images.githubusercontent.com/7057924/211859724-6becadcf-39f1-4920-a990-8d3a0ea34d72.png)

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

## Game mode

Use the desktop icon to Return to Gaming Mode. You should find Outlands in your library under the Non-steam games category. Simply run it and it should open. You'll need to use the mouse (hold the Steam button and use the right trackpad or stick) to press Play Now.

When ClassicUO launches, you may find that the Razor window is taking up the whole screen. Press the Steam button and you should see the ``Switch Windows`` section showing Razor and ClassicUO. Select ClassicUO and you should see the login screen.

If window switching doesn't appear to work, exit the game and into Steam Deck settings (Steam button, Settings). In the System page, use the ``Enable Developer Mode`` option. You should now be able to use window switching to switch between ClassicUO and Razor.

If ClassicUO has black borders on the left and right sides, go into ClassicUO's options, Video, and enable Borderless Window.
