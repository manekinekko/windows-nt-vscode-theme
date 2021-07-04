# A Windows NT/2000 theme for VS Code

<p align="center">
  <img src="https://raw.githubusercontent.com/manekinekko/windows-nt-vscode-theme/main/docs/windows-nt-vs-code-theme-banner.jpg">
</p>


## Install

### From Visual Studio Marketplace

1. Go to [Visula Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=wassimdev.windows-nt-vscode-theme).
2. Click on the "Install" button.
3. Then [select a theme](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme). Currently the following themes are available:
    - `Windows NT`

### From VS Code

1. Open the extension view <kbd>⇧⌘X</kbd>
2. Search for `@category:"themes" windows NT`
3. Locate the theme and click "Install"

## Selecting the Color Theme

1. In VS Code, open the Color Theme picker with `File > Preferences > Color Theme`. (`Code > Preferences > Color Theme` on macOS).
1. You can also use the keyboard shortcut <kbd>⌘K ⌘T</kbd> to display the picker.
1. Use the cursor keys to preview.
1. Select "Windows NT" and press Enter.

## Override this theme

You can also override this (or any other) theme in your personal config file. Please follow the guide in the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

## Contribute

1. Clone and open this [repo](https://github.com/manekinekko/windows-nt-vscode-theme) in VS Code
1. Press `F5` to open a new window with your extension loaded
2. Open `Code > Preferences > Color Theme` <kbd>⌘k ⌘t</kbd> and pick the "Windows NT"
3. Update files under [`/themes/`](https://github.com/manekinekko/windows-nt-vscode-theme/blob/main/themes/) or [`/fileicons/`](https://github.com/manekinekko/windows-nt-vscode-theme/blob/main/fileicons/) folders.
    - **UI**: For all changes to the "outer UI", like (status bar, file navigation etc.), take a look at the [Theme Color](https://code.visualstudio.com/api/references/theme-color) reference.
    - **Syntax**: For changes to the "code highlighting", examine the syntax scopes by invoking the [`Developer: Inspect Editor Tokens and Scopes`](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide#scope-inspector) command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac) in the Extension Development Host window.
    - **Icons**: For changes to the icons, take a look at the [File Icon Theme](https://code.visualstudio.com/api/extension-guides/file-icon-theme) reference.
4. Commit your changes and open a PR.

Note:

- Changes to the theme files are automatically applied to the Extension Development Host window, so no reloading should be necessary.

## Publish

1. Squash and merge Pull Requests that are ready to be published into `main`.
1. Run `npm run package -- [version]`. Follow the [SemVer](https://semver.org) convention and replace `[version]` with one of the following options:
    - `patch` for bug fixes
    - `minor` for improvements
    - `major` for breaking or bigger changes
1. Push your changes to GitHub
1. Run `npm run release` to publish the theme on the Marketplace.

## Credits

This theme was inspired by the official Windows 98 / Windows 2000 / Windows NT themes. The Code Editor theme scheme was inspired by the default Light (Visual Studio) theme shipped by VS Code. File icons are credited to [Alex Meub](https://win98icons.alexmeub.com/).

