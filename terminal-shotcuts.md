# Essential Command Line Editing Shortcuts

## Cursor Movement
- `Ctrl + A` → Move to the **beginning** of the line  
- `Ctrl + E` → Move to the **end** of the line  
- `Ctrl + U` → **Cut** (delete) everything **before** the cursor  
- `Ctrl + K` → **Cut** (delete) everything **after** the cursor  
- `Ctrl + W` → Delete the word **before** the cursor  
- `Ctrl + D` → Delete the **current** character (same as `Delete` key)  
- `Ctrl + H` → Delete the **previous** character (same as `Backspace`)  
- `Alt + D` → Delete the **word** after the cursor  

## Navigation by Word
- `Alt + B` → Move **backward** one word  
- `Alt + F` → Move **forward** one word  

## Undo & Redo
- `Ctrl + _` or `Ctrl + X, Ctrl + U` → **Undo** the last edit  
- `Ctrl + Y` → **Paste** (yank) the last deleted text  

## History Navigation
- `Ctrl + R` → **Reverse search** through command history  
- `Ctrl + G` → **Cancel** reverse search  
- `Ctrl + P` → Previous command (same as Up arrow)  
- `Ctrl + N` → Next command (same as Down arrow)  

## Process Control
- `Ctrl + C` → **Kill** the current command  
- `Ctrl + Z` → **Suspend** the current command (background it with `bg`)  

## Transpose & Modify Text
- `Ctrl + T` → Swap the last two **characters**  
- `Alt + T` → Swap the last two **words**  
- `Alt + U` → Uppercase **word**  
- `Alt + L` → Lowercase **word**  
- `Alt + C` → Capitalize **word**  

## Bang (`!`) Expansion
- `!!` → Run the last command again  
- `!xyz` → Run the last command starting with `xyz`  
- `!$` → Use the last argument from the previous command  
- `^old^new` → Replace `old` with `new` in the last command and run it  

These shortcuts will **massively speed up** your terminal workflow. 🚀
