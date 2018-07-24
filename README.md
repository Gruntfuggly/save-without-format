# Save Without Format

This simply allows you to save without triggering the auto format. Useful if your formatter insists on doing some odd stuff (I'm looking at you clang-format) with files in a repository that you want to make minimal changes to.

When called, the function takes note of the current "formatOnSave" setting, sets the flag to false, saves the file and then restores the original setting.

The default keybinding is **Alt + Shift + S**
On Mac: **CMD + Alt + S**

*Note: Only the global setting is taken into account. Currently, language specific settings will still remain in play.*

## Installing

You can install the latest version of the extension via the Visual Studio Marketplace [here](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.save-without-format).

Alternatively, open Visual Studio code, press `Ctrl+P` or `Cmd+P` and type:

    > ext install save-without-format
