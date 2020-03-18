# electron-ts-vscode-template

> **If you want to develop Electron app with the React, move on to https://github.com/phoihos/electron-react-ts-vscode-template.**


**Clone and run for a quick way to see Electron in action.**

This is a minimal Electron application based on the [Quick Start Guide](http://electron.atom.io/docs/tutorial/quick-start) within the Electron documentation.

**Use this app along with the [Electron API Demos](http://electron.atom.io/#get-started) app for API code examples to help you get started.**

A basic Electron application needs just these files:

- `./package.json` - Points to the app's main file and lists its details and dependencies.
- `./src/main.ts` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `./src/index.html` - A web page to render. This is the app's **renderer process**.

You can learn more about each of these components within the [Quick Start Guide](http://electron.atom.io/docs/tutorial/quick-start).

## Getting Started

1. Make sure you're running the latest version of VS Code.
2. Also make sure the latest version of the [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) extension is installed in VS Code.
3. To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:
    >
    ```
    # Clone this repository
    git clone https://github.com/phoihos/electron-ts-vscode-template.git
    # Go into the repository directory
    cd electron-ts-vscode-template
    # Install dependencies
    npm install
    # Run VS Code on the repository directory
    code .
    ```

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## Debugging

1. Go to the Run view and select **'Run Electron App'**
2. Set breakpoints in any of the files.

Note: The breakpoint in the **renderer process** will not be hit immediately while Chrome Debugger attaching to Electron App. If you know about solving this issue, please open an issue on [Github](https://github.com/phoihos/electron-ts-vscode-template/issues).

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
