# BackpackBattles[Modded]

Modified version of BackpackBattles to allow the install of custom skins.

## Important

### Updating
The creation of this modded client requires altering of the source code. This means as the game is patched new versions need to be manually updated and uploaded. However using an older version of the game will still allow you to play. 

### Unintended uses
This was put together with the intented purpose of allowing custom skins to be created and installed as easily as possible. However due to the way I have done this, by loading and overridng source code with godot .pck files, this can potentially be used to create other mods if you know what to override in the .pck. These possibilites are untested, however since this is a client based game, any alterations shouldn't have an effect on other players experience and is purely for your own use.

### Skin Costs
Due to the obvious flaw with allowing custom skins and skins having trophy costs, I have disabled the cost of all skins inside of the modded client. This will not unlock the skins for you if you return to the unmodded client, however it does mean you can use any skin parts you want for free while using the modded client.


## How to install client
- Open [Steam]
- Right click on [Backpack Battles Demo]
- [Properties] > [Installed Files] > [Browse]
- Backup or remove existing [BackpackBattles.pck]
- Replace with modded [BackpackBattles.pck]
- Launch [Backpack Battles Demo]

## How to install skins
- Run the modded client once (this will allow it to create missing folders for skin storage)
- Go to your systems local files
  - Windows : %APPDATA%\Godot\app_userdata\Backpack Battles
  - Linux : ~/.local/share/godot/app_userdata/Backpack Battles
  - MacOS : ~/Library/Application Support/Godot/app_userdata/Backpack Battles
- Place desired .pck skin files in [skins] folder
- Launch [Backpack Battles Demo]
