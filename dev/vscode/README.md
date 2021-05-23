# Setup for Visual Studio Code

### Step 1:
Install the following extensions:
* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

### Step 2:
Add a `.vscode` folder to the root of your project and add a `extensions.json` file with the following content:
```bash
{
  "recommendations": [
    "dbaeumer.vscode-eslint", 
    "esbenp.prettier-vscode"
  ]
}
```

### Step 3:
Fire up the [command palette](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette) and type "open workspace settings (JSON)". Put the following code inside the json file:
```bash
{
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.formatOnSave": false
  },
  "[javascriptreact]": {
    "editor.formatOnSave": false
  }
}
```

If you have trouble using the command palette just add a `settings.json` file with the content above inside your `.vscode` folder

## Directory Layout
This should be your final directory layout for forty-percent-web. If it doesn't match, you possibly made an error. Feel free to contact Joshua Liang for assistance. 

```
├──forty-percent-web/             # Parent app directory
│   ├── .vscode/                   # Visual studio code parent directory
│   |   ├── extensions.json        # Visual studio code extensions
│   |   └── settings.json          # Visual studio code settings
│   ├── config/                    # Create-react-app ejected config
│   ├── public/
│   ├── scripts/
│   ├── src/
│   ├── .eslintrc.json
│   ├── .gitignore
│   ├── package-lock.json
│   ├── package.json
│   └── README.md
```
