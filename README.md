# vscodesetting
VSCode setting for ASMR with python

# VSCode Extension
1. Python | Microsoft
2. Pylance | Microsoft
3. Jupyter | Microsoft
4. Jypyter Keymap
5. Material Icon Theme
6. Black Formatter | Microsoft
7. Pylint | Microsoft
8. autoDocString | nils Werner
10. Code Runner | Jun Han
11. TODO Highlight v2 | Jonathan Clark
12. Tabnine: IA Chat

# Hidden Panels 
- commands 
ctl+shift+p
- View: Toogle Breadcrumbs
- Menu Bar
- Activity Bar
- Window Command Center

# Key bindings for create new file and folders
```
[
    {
        "key": "ctrl+n",
        "command": "explorer.newFile",
        "when": "!editorFocus"
    },
    {
        "key": "ctrl+shift+n",
        "command": "explorer.newFolder",
        "when": "!editorFocus"
    }
]
```