### For fast setup React Native

```json
{
  "workbench.colorTheme": "Dracula Soft",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.suggestSelection": "first",
  "xmlTools": {
    "enforcePrettySelfClosingTagOnFormat": true
  },
  "editor.formatOnPaste": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "turboConsoleLog.addSemicolonInTheEnd": true,
  "turboConsoleLog.delimiterInsideMessage": "-",
  "turboConsoleLog.includeFileNameAndLineNum": false,
  "turboConsoleLog.insertEnclosingClass": false,
  "turboConsoleLog.insertEnclosingFunction": false,
  "turboConsoleLog.logMessagePrefix": "🚀",
  "turboConsoleLog.quote": "'",
  "guides.normal.width": 0.8,
  "cSpell.language": "en,ru-RU,en-GB,en-US",
  "actionButtons": {
    "defaultColor": "#ff0034", // Can also use string color names.
    "loadNpmCommands": false, // Disables automatic generation of actions for npm commands.
    "reloadButton": "♻️", // Custom reload button text or icon (default ↻). null value enables automatic reload on configuration change
    "commands": [
      {
        "name": "📱 run android",
        "color": "green",
        "singleInstance": true,
        "command": "yarn android" // This is executed in the terminal.
      },
      {
        "name": "Full clear cache",
        "color": "red",
        "command": "watchman watch-del-all && rm -f yarn.lock && cd android && ./gradlew clean && cd .. && yarn && yarn start --reset-cache"
      },
      {
        "name": "📱 run ios",
        "color": "pink",
        "command": "yarn ios"
      },
      {
        "name": "😎 my ios",
        "color": "pink",
        "command": "yarn ios --device \"iPhone 13 pro max\""
      },
      {
        "name": "Full re-install ios",
        "color": "red",
        "command": "yarn && cd ios && pod install && pod update && cd .."
      },
      {
        "name": "Run metro no cache",
        "color": "white",
        "command": "yarn start --reset-cache"
      }
    ]
  },
  "editor.minimap.enabled": false,
  "editor.inlineSuggest.enabled": true,
  "solidity.telemetry": true,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "window.zoomLevel": 1,
  "git.openRepositoryInParentFolders": "never"
}
```

Для добавления команды code:
<https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line>

```shell
code --install-extension aaron-bond.better-comments
code --install-extension alefragnani.project-manager
code --install-extension apollographql.vscode-apollo
code --install-extension bradlc.vscode-tailwindcss
code --install-extension ChakrounAnas.turbo-console-log
code --install-extension christian-kohler.path-intellisense
code --install-extension codezombiech.gitignore
code --install-extension dbaeumer.vscode-eslint
code --install-extension donjayamanne.git-extension-pack
code --install-extension donjayamanne.githistory
code --install-extension DotJoshJohnson.xml
code --install-extension dracula-theme.theme-dracula
code --install-extension dzannotti.vscode-babel-coloring
code --install-extension eamodio.gitlens
code --install-extension esbenp.prettier-vscode
code --install-extension formulahendry.auto-rename-tag
code --install-extension GitHub.copilot
code --install-extension GraphQL.vscode-graphql
code --install-extension GraphQL.vscode-graphql-syntax
code --install-extension Kasik96.swift
code --install-extension kumar-harsh.graphql-for-vscode
code --install-extension lostintangent.vsls-whiteboard
code --install-extension mathiasfrohlich.Kotlin
code --install-extension mikestead.dotenv
code --install-extension ms-vsliveshare.vsliveshare
code --install-extension msjsdiag.vscode-react-native
code --install-extension naumovs.color-highlight
code --install-extension NomicFoundation.hardhat-solidity
code --install-extension Orta.vscode-jest
code --install-extension redhat.vscode-yaml
code --install-extension seunlanlege.action-buttons
code --install-extension sirmspencer.vscode-autohide
code --install-extension spywhere.guides
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension streetsidesoftware.code-spell-checker-russian
code --install-extension TTOOWA.in-your-face-incredible
code --install-extension xabikos.JavaScriptSnippets
code --install-extension ziyasal.vscode-open-in-github
```

#### Safari extensions

JSON peep
Polyglot
