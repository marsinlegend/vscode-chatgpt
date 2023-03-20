### How to run

- Clone the repository to your local machine
- On the root directory, run `yarn` command to install the dependencies listed in `package.json`
- Within VS Code - run the project by simply hitting F5.
- You could also create a 'vsix' package from the source-code and <a href="https://code.visualstudio.com/docs/editor/extension-marketplace#_install-from-a-vsix">install manually</a>.

### How to build `vsix`

[publishing-extension](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)

```bash
npm install -g @vscode/vsce

cd vscode-chatgpt

vsce package
```

go to extensions tab of vscode click `...` button and select `install from vsix`

