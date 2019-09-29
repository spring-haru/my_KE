# .json files for Karabiner-Elements

## Japanese and others
* JIS Keyboard
* `My_Key_Remap_for_KE.json` (`かな` and `英数` are Japanese keys)
  * 「`かな`」-> `Ctrl` if alone, otherwise 「`かな`」
  * 「`英数`」 -> `Option` if alone, otherwise 「`英数`」
  * `Ctrl` -> `escape` if alone, otherwise `Ctrl`
  * 「`ろ`」(underscore) -> `\` (backslash)
  * Alfred : Buffer file management
  * Double `cmd-q` -> `cmd-q`
  * Ctrl+英数+hjkl -> up/down/left/right in Terminal, iTerm2, MacVim only
  * Semicolon -> ESC for Terminal, iTerm, MacVim only
  * `Ctrl-semicolon` -> `Ctrl-Option-semicolon`
  * Ctrl+h  -> Delete or Option+Delete (except Termina, iTerm2, MacVim)

## Yet Another Vim Mode
* `Normal_start.json`
  * `Ctrl-semicon` -> `semicolon`
  * `semicolon` : start Normal Mode

* `Normal_basic-movement.json`
  * `iIaAoO` : exit Normal Mode
  * `jkhl` : basic movements in Normal Mode
  * `web0$G` : various movements in Normal Mode
  * `Cmd-j` & `Cmd-k` : 5 lines down & up in Normal Mode
  * `space` & `Shift-space` : 20 lines down & Up in Normal Mode
  * `Shift-j` : join lines
  * `x` : delete
  * `Shift-d` : delete the rest of a line
  * `p` : paste
  * `u` : undo
  * `Ctrl-r` : redo

* `Normal_double-press.json`
  * `gg` : jump to the top line
  * `dd` : delete a whole line
  * `dw` : delete a word
  * `zz` : move the cursor to the middle of the screen
  * `yy` : yank a line

* `Visual_basics.json`
  * `v` : start Visual Mode
  * `Shift-v` : start Visual Model selecting a whole line
  * `jkhl` : basic movement in Visual Mode
  * `web0$G` : various movement in Visual Mode
  * `space` & `Shift-space` : 20 lines down & Up in Visual Mode
  * `x` : delete in Visual Mode (copy)
  * `y` : yank in Visual Mode
  * `p` : paste

* `Disable_keys.json`
  * `cntq` : keys disabled in Normal Mode
  * `inv` : keys disabled in Visual Mode

* [Hammerspoon](https://www.hammerspoon.org) is used to show
  * Red boarders in Normal Mode
  * Blue boarders in Visual Mode

My hammerspoon files can be found [here](https://github.com/spring-haru/.hammerspoon).
