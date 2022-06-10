# vscode-settings
just my preferred settings for vscode 




```
{
    "editor.minimap.enabled": false,
    "editor.occurrencesHighlight": false,
    "workbench.settings.editor": "json",
    "workbench.settings.useSplitJSON": true,
    "workbench.settings.openDefaultKeybindings": true,
    "window.openFoldersInNewWindow": "on",
    "workbench.editor.enablePreview": false,
    "editor.copyWithSyntaxHighlighting": false,
    
    "explorer.autoReveal": false,
    "explorer.compactFolders": false,
    "editor.codeLens": false,
    "omnisharp.useGlobalMono": "always",
    "editor.stopRenderingLineAfter" : -1,

    "git.enabled": false,
    
    "files.exclude": {
      "**/.git": false,
      "**/.gitignore": false,
      "**/.svn": true,
      "**/.hg": true,
      "**/*.meta": true,
      "**/CVS": true,
      "**/.DS_Store": true
    },
    "window.title": "${rootName}${separator}${dirty}${activeEditorShort}${separator}",
    "shellLauncher.shells.windows": [      
        {
        "shell": "C:\\Program Files\\Git\\bin\\bash.exe",
        "label": "Git bash"
        },
        {
        "shell": "C:\\Windows\\System32\\bash.exe",
        "label": "WSL Bash"
        },
        {
          "shell": "C:\\Windows\\System32\\cmd.exe",
          "label": "cmd"
        },
        {
          "shell": "C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
          "label": "PowerShell"
        },
      
      ],
      "terminal.explorerKind": "external",

      "terminal.integrated.profiles.windows": {
        "PowerShell": null,
        "Git Bash": {
          "source": "Git Bash"
        },
        "Command Prompt": {
          "path": [
            "${env:windir}\\Sysnative\\cmd.exe",
            "${env:windir}\\System32\\cmd.exe"
          ],
          "args": [],
          "icon": "terminal-cmd"
        }
        
      },
      "terminal.integrated.defaultProfile.windows": "Git Bash",
      "workbench.editorAssociations": {
        "*.html": "default"
      },
      "security.workspace.trust.untrustedFiles": "open",
      "svg.preview.mode": "svg",
      "explorer.confirmDragAndDrop": false,

      "files.associations": {
        "*.uxml": "xml",
        "*.jslib": "javascript",        
        "*.jspre": "javascript"
      }
}
```
