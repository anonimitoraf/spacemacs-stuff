## Important keybindings

---
## General
Desc | Keys
-- | --
Un/comment lines | `SPC c l`
Visual surround | `s <char>` 
Search for a file | `SPC f f`
Open file (after searching for it) | `C-c o`
Clear contents of helm input | `C M B-SPC`
Open file in a split window from helm | `C-c o`
Go to definition | `g d`
Go to definition (other window) | `g D`
Toggle cursor 1 position back and forth | `''`
Close window | `SPC w d`
Open terminal | `SPC '`
Search command by keybindings | `C-h b`
(Un\|Re)do window layout | `C-c` `Left`/`Right`
Bring selected line on top/middle/bottom of window | `zt`/`zz`/`zb`
Move selected line 1 upwards/downwards the window | `C-e`/`C-y`
Indent region | `SPC j =`
Indent region (more comprehensive but takes longer) | `SPC m =`
Open dotfile | `SPC f e d`

---
## Buffers (`SPC b)`
Desc | Keys
-- | --
Show all | `b`
Next | `n`
Previous | `p`
Close | `d`

---
## Neotree
Desc | Keys
-- | --
Create file/dir (if path ends with /) | `C-c C-n`
Delete file/dir | `C-c C-d`
Rename file/dir | `C-c C-r`
Change root dir. NOTE: If nothing is selected, a prompt pops up| `R`

---
## Org-mode
Desc | Keys
-- | --
New bullet point | `C-Enter`
Fold/unfold cycle | `Tab`
Fold/unfold cycle (whole file) | `S-Tab`
Moving bullet points with children following | `M-<vim-nav-keys>`
Task/Done cycle for bullet point | `t`
Only show tasks | `, T`
Show tasks completion count | Insert next to heading `[/]` then `, ,`
Show tasks completion percent | Insert next to heading `[%]` then  `, ,`
Create task  | `- [ ] <Task Description>`
Mark task as done | `, ,`
Add file to agenda | `C-c [`
Open options for agenda | `SPC a o o`
Agenda view | `SPC a o a`
Todo view | `SPC a o t`
Move forward/backward in agenda view | `b`/`f`
Create deadline | `, d`
Create start time  | `, s`
Export | `, e e`

---
## Clojure
### REPL
Desc | Keys
-- | --
Start REPL | `SPC m s i`
Clear REPL | `SPC m s c`
Eval buffer | `SPC m e b`
Eval region (NOTE: needs evaluated buffer) | `SPC m e r`
Debug mode | `SPC m d b`

### Refactoring (`SPC m r`)
Desc | Keys
-- | --
Rename selected symbol | `r s`
Add import to ns | `a i`
Add require to ns | `a r`
Add use to ns | `a u`
Find usages | `f u`
Create function from selected word | `f e`
Introduce `let` | `i l`

### Convert collection to (`SPC m r c`):
Desc | Keys
-- | --
 list | `(`
 quoted list | `'`
 map | `{`
 set | `#`
 vector | `[`

### Structured editing (`SPC k`)
Desc | Keys
-- | --
Un/Wrap | `W` \ `w`
Slurp backward/forward | `S` \ `s`
Barf backward/forward | `B` \ `b`

### Help (`SPC m h`)
Desc | Keys
-- | --
Apropos (Shows related functions, etc) | `a`
Doc (NOTE: If cursor is on symbol, shows doc for symbol)| `h` (or `S-k`)
Browse namespace | `n`

---
## Markdown
Desc | Keys
-- | --
Markdown live-preview | `SPC m c P`
