Getting Started
=============

Welcome to MacroKey, getting started is easy! This doc will show you how to get up and running with it.

-------------------

Installation
-------

Install Forge
^^^^^^^
To install Forge, head to the `Minecraft Forge download site`_, here you can download forge for the Minecraft version you wish to use. After downloading, run the `.jar` file. Make sure `Install Client` is checked, and press `OK`.

**Note:** Older versions of Minecraft may require you to have run a vanilla installation at least once

Install MacroKey
^^^^^^^
You can download the mod through one of the :doc:`official mirrors <links>`. When downloading, take note of the Minecraft version that the mod supports. The mod will not load on a game version it does not support.

.. note:: | When supporting multiple versions, the patch field will contain an `x`.
		  | *i.e.* when `1.12`, `1.12.1` & `1.12.2` are supported, the version in the title will be `1.12.x`

After downloading MacroKey, open the `.minecraft` directory (`Win + R` -> `%appdata%/.minecraft`). If a mods directory does not already exist, you can create one here. After that, you can drag the downloaded `MacroKey .jar` file into it.

Verifying Installation
^^^^^^^
To verify everything is installed correctly, start Minecraft, making sure that you are starting up the Forge instance. Once Minecraft has started, click on the Mods button. Here `MacroKey` should be listed.

--------------------

MacroKey Rundown
----------

MacroKey adds a few concepts into Minecraft, these concepts are Macro's & Layers.

**Macro's** are the main concept of the mod, they add an idea of connecting a chat message to a key press.

**Layers** allow you to group Macro's together that you use frequently on different occasions. This is, for example, useful if you want to use the same key for different commands, when on different servers.

MacroKey tries to add as much functionality, all while keeping it as logical and user-friendly as possible, this statement is mainly reflected in GUI's.
The mod adds various screens to make the management of your settings easy.

---------------------

Setting up your first Macro
----------

Open the Management GUI, for this you have two options:
  - Go to Settings -> MacroKey Keybinding
  - Press the MacroKey Management key while ingame (default: `k`)

Within Management, at the right bottom you can see the Create Macro button. Clicking this button will open the screen for adding macros to your configuration. When creating a new Macro, you will have to specify:

- The chat message you want to send
    When specifying a command, you will have to prefix it with a slash (`/`), this is to keep support for sending normal chat messages with MacroKey.
- The trigger (key) that should be pressed to activate the Macro
		The trigger can be any key on your keyboard, with exception to special macro buttons your keyboard may have. In theory, the trigger is optional. The Macro will, however, never be activated without a trigger.
- If the command should repeat
		When enabling this setting, the command will repeat as long as you are pressing the specified key. The delay can be configured.
- Should the macro be active
		Disabling the Macro has the same effect as not specifying a trigger. This setting allows you to keep your current trigger, and just ignore it.

After adding all information requested, you can press save. You will be redirected to the Management screen, here the macro you just added will be shown. At this point you can confirm that the Macro is saved, and it is usable in-game.


.. _Minecraft Forge download site: https://files.minecraftforge.net
