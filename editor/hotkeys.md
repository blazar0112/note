# Hotkeys

- Compare hotkeys and try set to most consistent.
- List Keyboard Shortcut setting name if configurable.
- Mnemonics
    - Alt+Arrow: Move
    - `S`hift+Alt+Arrow: `S`elect
    - `C`trl+Alt+Arrow: `C`opy

## Vertical Select

| Editor | Setting | Default | Reconfigure |
| - | - | - | - |
| QtCreator | N/A | Shift+Alt+Arrows | |
| Notepad++ | N/A | Shift+Alt+Arrows | |
| Visual Studio | Edit.LineUpExtendColumn | Shift+Alt+Arrows | |
| VSCode | cursorUpSelect | Ctrl+Shift+Alt+Arrows | Shift+Alt+Arrows |
| vim | Blockwise Visual Mode | Ctrl+V | |

- Note for VSCode:
    - There's also keyboard shortcuts to add cursor vertically: `Add Cursor Above/Below`: `Ctrl+Alt+Up/Down`.
- Note for vim: It looks strange when insert to select block
    - `Ctrl+V`: enter blockwise visual mode
    - `Arrow`s to select block
    - `Shift+I`: enter insert mode (not showing block but actually is)
    - Enter anything want to insert.
    - `Esc`, `Esc`: escape insert mode, then visual mode and it insert to all lines in block

## Copy Line Down

| Editor | Setting | Default | Reconfigure |
| - | - | - | - |
| QtCreator | CopyLineUp/Down | Ctrl+Alt+Up/Down | |
| Notepad++ | N/A | Ctrl+D (when not selecting) | |
| Visual Studio | Edit.Duplicate | Ctrl+D (when not selecting) | |
| VSCode | Copy Line Up/Down | Shift+Alt+Up/Down | Ctrl+Alt+Up/Down |
| vim | | yyp | |

## Move Line Up/Down

| Editor | Setting | Default | Reconfigure |
| - | - | - | - |
| QtCreator | MoveLineUp/Down | Ctrl+Shift+Up/Down | Alt+Up/Down |
| Notepad++ | Move Up/Down Current Line (Edit) | Ctrl+Shift+Up/Down | Alt+Up/Down |
| Visual Studio | Edit.MoveSelectedLinesUp/Down | Alt+Up/Down (single line when not selecting) | |
| VSCode | Move Line Up/Down | Alt+Up/Down | |
| vim | | ddkP/ddp | |
