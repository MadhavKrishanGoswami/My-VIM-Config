### Neovim Keymap Cheatsheet

#### General Commands
- **Clear search highlights**: `<leader>nh` (Space + n + h)

#### Number Manipulation
- **Increment number under cursor**: `<leader>+` (Space + +)
- **Decrement number under cursor**: `<leader>-` (Space + -)

#### Window Management
- **Split window vertically**: `<leader>sv` (Space + s + v)
- **Split window horizontally**: `<leader>sh` (Space + s + h)
- **Equalize split window sizes**: `<leader>se` (Space + s + e)
- **Close current split window**: `<leader>sx` (Space + s + x)
- **Maximize/minimize current split**: `<leader>sm` (Space + s + m)

#### Tab Management
- **Open new tab**: `<leader>to` (Space + t + o)
- **Close current tab**: `<leader>tx` (Space + t + x)
- **Go to next tab**: `<leader>tn` (Space + t + n)
- **Go to previous tab**: `<leader>tp` (Space + t + p)
- **Open current buffer in new tab**: `<leader>tf` (Space + t + f)

#### File Explorer (NvimTree)
- **Toggle file explorer**: `<leader>ee` (Space + e + e)
- **Toggle file explorer for current file**: `<leader>ef` (Space + e + f)
- **Collapse file explorer**: `<leader>ec` (Space + e + c)
- **Refresh file explorer**: `<leader>er` (Space + e + r)

#### Fuzzy Finder (Telescope)
- **Find files in current directory**: `<leader>ff` (Space + f + f)
- **Find recent files**: `<leader>fr` (Space + f + r)
- **Search for string in current directory**: `<leader>fs` (Space + f + s)
- **Search for string under cursor in current directory**: `<leader>fc` (Space + f + c)
- **Find TODOs**: `<leader>ft` (Space + f + t)

#### Code Suggestions (cmp)
- **Previous suggestion**: `<C-k>` (Ctrl + k)
- **Next suggestion**: `<C-j>` (Ctrl + j)
- **Scroll documentation up**: `<C-b>` (Ctrl + b)
- **Scroll documentation down**: `<C-f>` (Ctrl + f)
- **Show completion suggestions**: `<C-Space>` (Ctrl + Space)
- **Close completion window**: `<C-e>` (Ctrl + e)
- **Confirm selection**: `<CR>` (Enter)

#### LSP Keymaps
- **Show LSP references**: `gR` (g + R)
- **Go to declaration**: `gD` (g + D)
- **Show LSP definitions**: `gd` (g + d)
- **Show LSP implementations**: `gi` (g + i)
- **Show LSP type definitions**: `gt` (g + t)
- **See available code actions**: `<leader>ca` (Space + c + a) (in normal and visual mode)
- **Smart rename**: `<leader>rn` (Space + r + n)
- **Show buffer diagnostics**: `<leader>D` (Space + D)
- **Show line diagnostics**: `<leader>d` (Space + d)
- **Go to previous diagnostic**: `[d` ([ + d)
- **Go to next diagnostic**: `]d` (] + d)
- **Show documentation for what is under cursor**: `K`
- **Restart LSP**: `<leader>rs` (Space + r + s)

#### Commenting
- **Comment out a line**: `gcc`
- **Comment out a block**: `gc`

#### Substitution
- **Substitute with motion**: `s`
- **Substitute line**: `ss`
- **Substitute to end of line**: `S`
- **Substitute in visual mode**: `s`

#### Code Actions
- **Trigger code action**: `<leader>ca` (Space + c + a)
- **Rename symbol under cursor**: `<leader>rm` (Space + r + m)

#### Trouble List
- **Toggle trouble list**: `<leader>xx` (Space + x + x)
- **Show workspace diagnostics**: `<leader>xw` (Space + x + w)
- **Show document diagnostics**: `<leader>xd` (Space + x + d)
- **Show quickfix list**: `<leader>xq` (Space + x + q)
- **Show location list**: `<leader>xl` (Space + x + l)
- **Show TODOs in trouble list**: `<leader>xt` (Space + x + t)

#### Formatting
- **Format selected range or buffer**: `<leader>mp` (Space + m + p)

#### Line Navigation
- **Move down by relative line number**: `j<number>`
- **Move up by relative line number**: `k<number>`

#### TODO Comments
- **Mark TODO in comments**: `TODO:`
- **Mark BUG in comments**: `BUG:`
- **Mark HACK in comments**: `HACK:`

#### Fuzzy Finder Mappings (Telescope)
- **Move to previous result**: `<C-k>` (Ctrl + k)
- **Move to next result**: `<C-j>` (Ctrl + j)
- **Send selected to quickfix list**: `<C-q>` (Ctrl + q)
- **Open with Trouble**: `<C-t>` (Ctrl + t)

### LazyGit Cheat Sheet: Essential Commands

#### General Navigation
- **Move down/up in the list**: `j/k`
- **Toggle view (files, branches, commits, etc.)**: `tab`
- **Quit LazyGit**: `q`

#### Branches Panel
- **Checkout branch**: `c`
- **Create new branch**: `n`
- **Delete branch**: `D`
- **Merge branch**: `m`
- **Rebase current branch onto selected branch**: `r`

#### Commits Panel
- **View commit details**: `v`
- **Revert commit**: `r`
- **Reset to this commit**: `R`

#### Staging
- **Stage file/selected lines**: `s`
- **Stage all changes**: `S`
- **Unstage file/selected lines**: `u`
- **Unstage all changes**: `U`

#### Staging
- **Stage file/selected lines**: `s`
- **Stage all changes**: `S`
- **Unstage file/selected lines**: `u`
- **Unstage all changes**: `U`
