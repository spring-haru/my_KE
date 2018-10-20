# json files for Karabiner-Elements

## For Japanese and others
* File used
  * My_Key_Remap_for_KE.json
* Features
  * `semicolon` -> `escape` in MacVim only
  * `Ctrl-semicolon` -> `Ctrl-Option-semicolon`
  * `Ctrl+H`  -> `delete` (MacVim以外)
  * 「`かな`」-> `Ctrl` if alone, otherwise 「`かな`」
  * 「`英数`」 -> `fn` if alone, otherwise 「`英数`」
  * `fn+jkhl` : basic Vim movement
  * `Ctrl` -> `escape` if alone, otherwise Ctrl
  * 「`ろ`」(Underscore) -> backslash
  * Alfred : Buffer file management
  * Double `cmd-q` -> `cmd-q`

## A simple Vim mode for Karabiner-Elements
* Normal_start.json
  * `Ctrl-semicon` -> `semicolon`
  * `semicolon` : start Normal Mode

* Normal_basic-movement.json
  * `iIaAoO` : exit Normal Mode
  * `jkhl` : basic movement in Normal Mode
  * `web0$G` : various movement in Normal Mode
  * `Cmd-j` & `Cmd-k` : 5 lines down & up in Normal Mode
  * `space` & `Shift-space` : 20 lines down & Up in Normal Mode
  * `Shift-j` : join lines
  * `x` -> delete
  * `Shift-`d : delete the rest of a line
  * `p` : paste
  * `u` : undo
  * `Ctrl-r` : redo

* Normal_double-press.json
  * `gg` : jump to the top line
  * `dd` : delete a whole line
  * `dw` : delete a word
  * `zz` : move the cursor to the middle of the screen
  * `yy` : yank a line

* Visual_basics.json
  * `v` : start Visual Mode
  * `Shift-v` : start Visual Model selecting a whole line
  * `jkhl` : basic movement in Visual Mode
  * `web0$G` : various movement in Visual Mode
  * `space` & `Shift-space` : 20 lines down & Up in Visual Mode
  * `x` : delete in Visual Mode (copy)
  * `y` : yank in Visual Mode
  * `p` : paste

* Disable_keys.json
  * `cntq` : disabled in Normal Mode
  * `inv` : disabled in Visual Mode
