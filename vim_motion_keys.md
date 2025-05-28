# Vim Motion Keys Cheat Sheet

## 🔹 Basic Motions

| Key | Description |
|-----|-------------|
| `h` | Left (←) |
| `l` | Right (→) |
| `j` | Down (↓) |
| `k` | Up (↑) |
| `0` | Beginning of line |
| `^` | First non-blank character of line |
| `$` | End of line |
| `g_` | Last non-blank character of line |

## 🔹 Word Motions

| Key | Description |
|-----|-------------|
| `w` | Next word (start) |
| `W` | Next WORD (start, WORD includes punctuation) |
| `e` | End of word |
| `E` | End of WORD |
| `b` | Previous word (start) |
| `B` | Previous WORD (start) |
| `ge` | End of previous word |
| `gE` | End of previous WORD |

## 🔹 Paragraph and Sentence

| Key | Description |
|-----|-------------|
| `{` | Beginning of previous paragraph |
| `}` | Beginning of next paragraph |
| `(` | Beginning of sentence |
| `)` | End of sentence |

## 🔹 Character Insertion Positions

| Key | Description |
|-----|-------------|
| `i` | Insert before cursor |
| `I` | Insert at beginning of line |
| `a` | Insert after cursor |
| `A` | Insert at end of line |
| `o` | New line below |
| `O` | New line above |

## 🔹 Scrolling

| Key | Description |
|-----|-------------|
| `Ctrl-d` | Half-page down |
| `Ctrl-u` | Half-page up |
| `Ctrl-f` | Full page down |
| `Ctrl-b` | Full page up |
| `zz` | Center current line |
| `zt` | Move current line to top |
| `zb` | Move current line to bottom |

## 🔹 Search

| Key | Description |
|-----|-------------|
| `/pattern` | Search forward |
| `?pattern` | Search backward |
| `n` | Repeat search in same direction |
| `N` | Repeat in opposite direction |

## 🔹 Line and File Motions

| Key | Description |
|-----|-------------|
| `gg` | Go to first line |
| `G` | Go to last line |
| `nG` | Go to line `n` |
| `H` | Top of screen |
| `M` | Middle of screen |
| `L` | Bottom of screen |

## 🔹 Marks and Jumps

| Key | Description |
|-----|-------------|
| `'m` | Jump to mark `m` (linewise) |
| `` `m `` | Jump to mark `m` (exact position) |
| `%` | Matching parenthesis/bracket |
| `''` | Return to last jump position (line) |
| `` `` `` | Return to exact cursor location |

## 🔹 Text Objects (used with `d`, `y`, `c`, `v`, etc.)

| Key | Description |
|-----|-------------|
| `aw` / `iw` | A word / Inner word |
| `aW` / `iW` | A WORD / Inner WORD |
| `as` / `is` | A sentence / Inner sentence |
| `ap` / `ip` | A paragraph / Inner paragraph |
| `a"` / `i"` | A double-quoted string |
| `a'` / `i'` | A single-quoted string |
| `a)` / `i)` | A block in parentheses |
| `a]` / `i]` | A block in square brackets |
| `a}` / `i}` | A block in curly braces |
| `a>` / `i>` | A block in angle brackets |
| `at` / `it` | A tag block (e.g., HTML) |

## 🔹 Special Motions

| Key | Description |
|-----|-------------|
| `fx` | Move to next `x` on the line |
| `Fx` | Move to previous `x` |
| `tx` | Move before next `x` |
| `Tx` | Move before previous `x` |
| `;` | Repeat last `f`, `t`, `F`, or `T` |
| `,` | Repeat in opposite direction |
