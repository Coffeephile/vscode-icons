# vscode-icons
Bring icons to your VS Code.

In order to enable the extension just execute the command *Icons Enable*.

If you want to disable the icons execute the *Icons Disable* command instead.

### Windows users
**In Windows, make sure you run your VS Code in Administrator mode before enabling or disabling the icons!**

# Disclaimer
This extension modifies some VS Code files so use it at your own risk.
Currently, icons are not supported by the extension functionality that VS Code provides so this extension solves this issue by injecting code into two files:

- workbench.main.js
- workbench.main.css

The extension will keep a copy of the original files in case something goes wrong. That's what the disable command will do for you.

As this extension modifies VS Code files it will get disabled with every VS Code update. You will have to enable icons again via command palette.

Take into account that this extension is still in beta so you may find some bugs while playing with it. Please, report them to [the issues section of the Github's repo](https://github.com/robertohuertasm/vscode-icons/issues).

**Please, leave a review if you can so the VS Code Team can know that this is a very demanded feature. Maybe that would be enough so they can provide a proper way to extend the IDE regarding icons and customizations. ;D**

More extensions will be supported shortly!


# Screenshot
<img src="https://raw.githubusercontent.com/robertohuertasm/vscode-icons/master/screenshot.png" >


**Enjoy!**