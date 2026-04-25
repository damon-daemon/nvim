# Leader Key Shortcuts

All mappings use `<leader>` (Space). Press `<leader>` and wait to see which-key popup.

## Top-level

| Key | Action |
|-----|--------|
| `<leader>,` | Switch buffer (picker) |
| `<leader>/` | Search in project (grep) |
| `<leader>:` | Command history |
| `<leader>.` | Browse files (cwd) |
| `<leader><space>` | Find files (root) |
| `<leader>?` | Recent files |
| `<leader>\`` | Switch to other buffer |
| `<leader>-` | Split window below |
| `<leader>\|` | Split window right |
| `<leader>e` | File explorer (neo-tree, root) |
| `<leader>E` | File explorer (cwd) |
| `<leader>l` | Open Lazy plugin manager |
| `<leader>L` | LazyVim changelog |
| `<leader>K` | Keywordprg on word |
| `<leader>qq` | Quit all |

## `<leader>b` — buffers

| Key | Action |
|-----|--------|
| `<leader>bb` | Switch to other buffer |
| `<leader>bd` | Delete buffer |
| `<leader>bD` | Delete buffer + window |
| `<leader>bo` | Delete all other buffers |
| `<leader>bp` | Pin buffer |
| `<leader>bP` | Delete non-pinned buffers |

## `<leader>c` — code (LSP)

| Key | Action |
|-----|--------|
| `<leader>ca` | Code action |
| `<leader>cA` | Source action |
| `<leader>cd` | Line diagnostics (float) |
| `<leader>cf` | Format file/selection |
| `<leader>cF` | Format injected langs |
| `<leader>cr` | Rename symbol |
| `<leader>cR` | Rename file |
| `<leader>cs` | Document symbols |
| `<leader>cS` | Workspace symbols |
| `<leader>cl` | LSP info |
| `<leader>cm` | Mason (install LSPs/tools) |

## `<leader>d` — debug (DAP)

| Key | Action |
|-----|--------|
| `<leader>db` | Toggle breakpoint |
| `<leader>dB` | Breakpoint condition |
| `<leader>dc` | Continue |
| `<leader>dC` | Run to cursor |
| `<leader>dg` | Go to line (no stop) |
| `<leader>di` | Step into |
| `<leader>dj` | Down in stack |
| `<leader>dk` | Up in stack |
| `<leader>dl` | Run last |
| `<leader>do` | Step out |
| `<leader>dO` | Step over |
| `<leader>dp` | Pause |
| `<leader>dr` | Toggle REPL |
| `<leader>ds` | Session picker |
| `<leader>dt` | Terminate |
| `<leader>dw` | Widgets |
| `<leader>dpp` | Toggle profiler |
| `<leader>dph` | Toggle profiler highlights |

## `<leader>f` — file/find

| Key | Action |
|-----|--------|
| `<leader>ff` | Find files (root) |
| `<leader>fF` | Find files (cwd) |
| `<leader>fg` | Find git files |
| `<leader>fr` | Recent files |
| `<leader>fR` | Recent files (cwd) |
| `<leader>fb` | Buffers |
| `<leader>fc` | Find config files |
| `<leader>fn` | New file |
| `<leader>ft` | Terminal (root) |
| `<leader>fT` | Terminal (cwd) |

## `<leader>g` — git

| Key | Action |
|-----|--------|
| `<leader>gg` | Lazygit (root) |
| `<leader>gG` | Lazygit (cwd) |
| `<leader>gl` | Git log (root) |
| `<leader>gL` | Git log (cwd) |
| `<leader>gf` | Current file history |
| `<leader>gb` | Git blame line |
| `<leader>gB` | Git browse (open in browser) |
| `<leader>gY` | Git browse (copy URL) |
| `<leader>gs` | Git status |
| `<leader>gS` | Git stash |
| `<leader>gd` | Git diff (Snacks) |

## `<leader><tab>` — tabs

| Key | Action |
|-----|--------|
| `<leader><tab><tab>` | New tab |
| `<leader><tab>d` | Close tab |
| `<leader><tab>]` | Next tab |
| `<leader><tab>[` | Previous tab |
| `<leader><tab>f` | First tab |
| `<leader><tab>l` | Last tab |
| `<leader><tab>o` | Close other tabs |

## `<leader>s` — search (Snacks picker)

| Key | Action |
|-----|--------|
| `<leader>sg` | Grep (root) |
| `<leader>sG` | Grep (cwd) |
| `<leader>sw` | Grep word under cursor |
| `<leader>ss` | LSP document symbols |
| `<leader>sS` | LSP workspace symbols |
| `<leader>sd` | Diagnostics (document) |
| `<leader>sD` | Diagnostics (workspace) |
| `<leader>sc` | Command history |
| `<leader>sC` | Commands |
| `<leader>sh` | Help pages |
| `<leader>sH` | Highlight groups |
| `<leader>sk` | Keymaps |
| `<leader>sm` | Marks |
| `<leader>sM` | Man pages |
| `<leader>sr` | Resume last search |
| `<leader>sR` | Registers |
| `<leader>st` | Todo comments |
| `<leader>sT` | Todo/Fix/Fixme |
| `<leader>su` | Undo history |
| `<leader>sq` | Quickfix list |
| `<leader>sl` | Location list |

## `<leader>u` — UI toggles

| Key | Action |
|-----|--------|
| `<leader>uf` | Toggle auto-format (buffer) |
| `<leader>uF` | Toggle auto-format (global) |
| `<leader>us` | Toggle spelling |
| `<leader>uw` | Toggle word wrap |
| `<leader>ul` | Toggle line numbers |
| `<leader>uL` | Toggle relative numbers |
| `<leader>ud` | Toggle diagnostics |
| `<leader>uc` | Toggle conceal level |
| `<leader>uT` | Toggle Treesitter |
| `<leader>ub` | Toggle dark/light background |
| `<leader>uD` | Toggle dim inactive windows |
| `<leader>ua` | Toggle animations |
| `<leader>ug` | Toggle indent guides |
| `<leader>uS` | Toggle smooth scroll |
| `<leader>uh` | Toggle inlay hints |
| `<leader>ui` | Inspect highlight under cursor |
| `<leader>uI` | Inspect Treesitter tree |
| `<leader>uZ` | Toggle zoom (current window) |
| `<leader>uz` | Toggle zen mode |
| `<leader>uA` | Toggle tabline |

## `<leader>w` — windows

| Key | Action |
|-----|--------|
| `<leader>wd` | Delete window |
| `<leader>wm` | Toggle window zoom |
| `<leader>-` | Split below |
| `<leader>\|` | Split right |

## `<leader>x` — diagnostics/lists

| Key | Action |
|-----|--------|
| `<leader>xl` | Toggle location list |
| `<leader>xq` | Toggle quickfix list |
| `<leader>xx` | Trouble: diagnostics (document) |
| `<leader>xX` | Trouble: diagnostics (workspace) |
| `<leader>xL` | Trouble: location list |
| `<leader>xQ` | Trouble: quickfix list |
| `<leader>cs` | Trouble: symbols |
| `<leader>cS` | Trouble: LSP definitions/references |
