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

Once the bottle has been created, click on it to open it.

![image](https://user-images.githubusercontent.com/7057924/211855677-a10c2e80-ae69-4159-a406-73435cde2b03.png)

Go into Settings and switch the runner from soda to sys-wine

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
