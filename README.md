# TypeScript
VS Code

Plugins: Liver Server, Prettier

settings.json

{
  "workbench.colorTheme": "Origamid Next",
  "workbench.iconTheme": "origamid-next-icons",
  "editor.fontFamily": "IBM Plex Mono",
  "editor.fontSize": 16,
  "editor.lineHeight": 1.75,
  "editor.tabSize": 2,
  "workbench.startupEditor": "newUntitledFile",
  "editor.wordWrap": "on",
  "editor.minimap.renderCharacters": false,
  "telemetry.telemetryLevel": "off",
  "security.workspace.trust.untrustedFiles": "open",
  "breadcrumbs.filePath": "off",
  "outline.icons": false,
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true,
  "editor.formatOnSave": true,
  "html.format.wrapAttributes": "auto",
  "html.format.wrapLineLength": 0,
  "html.autoClosingTags": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "editor.colorDecorators": false,
  "color-highlight.markerType": "dot-before",
  "editor.minimap.enabled": false,
  "editor.accessibilitySupport": "off",
  "editor.bracketPairColorization.enabled": false,
  "emmet.excludeLanguages": ["markdown", "css"],
  "workbench.statusBar.visible": false,
  "workbench.editor.untitled.hint": "hidden",
  "editor.suggest.showInlineDetails": false,
  "terminal.integrated.fontSize": 14
}
script.ts e tsc
Os principais programas que executam JavaScript (browser/node), não conseguem executar TypeScript. Por isso precisamos de um compilador para gerar um arquivo JavaScript a partir de um TypeScript.

npm install -g typescript
tsc --init
tsconfig.json

{
  "compilerOptions": {
    "target": "ESNext",
    "strict": true
  }
}
tsc -w