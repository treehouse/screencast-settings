# Setup

* Copy the `.vscode` subdirectory into your project directory.
* In the Visual Studio Code menu, choose "File" -> "Open...".
* Navigate your project directory, and click the "Open" button.

Or, if you're in a hurry:

```
mkdir .vscode; curl https://raw.githubusercontent.com/treehouse/screencast-settings/master/visual_studio_code/.vscode/settings.json > .vscode/settings.json; code .
```

The project should then open with a zoomed-in interface and enlarged editor and terminal fonts.

# Notes

* `"window.zoomLevel"` increases Explorer (sidebar) font size.
* Because `"window.zoomLevel"` is increased, using 14-point fonts for the editor and Terminal is equivalent to an 18-point font normally.

You may wish to add these items to your workspace or user settings as well. We're not making them part of the default settings because they could be considered a matter of personal preference.

``` javascript
    // Prevents auto-complete from sometimes completing the wrong thing.
    "editor.acceptSuggestionOnCommitCharacter": false,
    // Prevents auto-complete from sometimes surprising you with the wrong completion when you're just trying to get to the next line.
    "editor.acceptSuggestionOnEnter": "off",
    // Most folks want auto-closing of brackets for daily coding, but if you're using scripts to simulate typing, auto-closing brackets can interfere with that.
    "editor.autoClosingBrackets": false,
```
