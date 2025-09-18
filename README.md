# VS Code Settings

- Font: [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous/)
- Theme: [Tokyo Night](https://github.com/tokyo-night/tokyo-night-vscode-theme)
- File Icons: [Material Icon Theme](https://github.com/material-extensions/vscode-material-icon-theme)

## Settings

```json
{
  // Visuals
  "editor.fontSize": 17,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.fontFamily": "Anonymous Pro",
  "editor.guides.bracketPairs": "active",
  "editor.lineNumbers": "interval",
  "editor.renderWhitespace": "boundary",
  "editor.fontLigatures": true,
  "editor.minimap.enabled": false,
  "editor.lineHeight": 0,
  "window.autoDetectColorScheme": true,
  "workbench.startupEditor": "none",
  "workbench.colorTheme": "Tokyo Night",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.fontAliasing": "antialiased",
  "workbench.editor.showTabs": "none",
  "workbench.sideBar.location": "left",
  "workbench.statusBar.visible": false,
  "workbench.list.smoothScrolling": true,
  "workbench.secondarySideBar.defaultVisibility": "hidden",
  "workbench.tree.indent": 10,
  "markdown.preview.fontSize": 36,

  // Editor
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.snippetSuggestions": "top",
  "editor.linkedEditing": true,
  "editor.suggestSelection": "first",
  "editor.wordWrap": "on",
  "editor.tabSize": 2,
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.inlineSuggest.enabled": true,
  "editor.unicodeHighlight.invisibleCharacters": false,
  "editor.detectIndentation": true,
  "editor.accessibilitySupport": "off",
  "terminal.integrated.fontSize": 16,
  "search.exclude": {
    "**/*.code-search": true,
    "**/*.snap": true,
    "**/*.svg": true,
    "**/.git": true,
    "**/.github": false,
    "**/.nuxt": true,
    "**/.output": true,
    "**/.pnpm": true,
    "**/.vscode": true,
    "**/.yarn": true,
    "**/assets": true,
    "**/bower_components": true,
    "**/dist/**": true,
    "**/logs": true,
    "**/node_modules": true,
    "**/out/**": true,
    "**/package-lock.json": true,
    "**/pnpm-lock.yaml": true,
    "**/public": true,
    "**/temp": true,
    "**/yarn.lock": true,
    "**/CHANGELOG*": true,
    "**/LICENSE*": true
  },
  "reactSnippets.settings.importReactOnTop": false,
  "http.proxyAuthorization": null,
  "files.autoSave": "onFocusChange",
  "window.zoomLevel": 1,
  "cSpell.enabled": true,
  "cSpell.enableFiletypes": ["mdx"],
  "diffEditor.ignoreTrimWhitespace": false,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "emmet.showAbbreviationSuggestions": false,
  "eslint.enable": true,
  "eslint.validate": ["react", "typescript", "html", "javascript"],
  "explorer.openEditors.visible": 1,
  "extensions.ignoreRecommendations": true,
  "git.autofetch": true,
  "git.openRepositoryInParentFolders": "never",
  "search.useIgnoreFiles": false

  // Formatter
  "prettier.semi": true,
  "prettier.singleQuote": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[handlebars]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[java]": {
    "editor.defaultFormatter": "redhat.java"
  },
  "[rust]": {
    "editor.defaultFormatter": "rust-lang.rust-analyzer"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  // Extensions
  "liveServer.settings.donotShowInfoMsg": true,
  "console-ninja.featureSet": "Community",
  "highlight-matching-tag.styles": {
    "opening": {
      "left": {
        "custom": {
          "borderWidth": "0 0 0 3px",
          "borderStyle": "solid",
          "borderColor": "yellow",
          "borderRadius": "5px"
        }
      },
      "right": {
        "custom": {
          "borderWidth": "0 3px 0 0",
          "borderStyle": "solid",
          "borderColor": "yellow",
          "borderRadius": "5px"
        }
      }
    }
  },
  "[prisma]": {
    "editor.defaultFormatter": "Prisma.prisma"
  },
  "prisma.showPrismaDataPlatformNotification": false,
}
```

## Extensions

- Tokyo Night
- Material Icon Theme
- Prettier
- indent-rainbow
- Auto Rename Tag
- Highlight Matching Tag
- Tailwind CSS IntelliSense
- ESLint
- Pretty TypeScript Errors
- ES7+ React/Redux/React-Native snippets
  - `rafce` - 快速创建 arrow function with export
  - `rfce` - 快速创建 regular function with export
- Console Ninja
- GitLens
- Import Cost
- Code Spell Checker
- Image preview
- HSL Color Preview
- Live Server

## Reference

- [CodeGraden/vscode-settings](https://github.com/CodingGarden/vscode-settings)
- [antfu/vscode-settings](https://github.com/antfu/vscode-settings)
