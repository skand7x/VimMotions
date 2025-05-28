# Vim Macros Guide

## 🔸 What is a Macro?

A macro in Vim is a recorded sequence of commands that you can replay multiple times.

## 🔸 How to Record a Macro

1. Press `q` followed by a **register** key (e.g., `a`–`z`) to start recording.
2. Perform any commands you want to record.
3. Press `q` again to stop recording.

Example: `qa` starts recording into register `a`. `q` stops recording.

## 🔸 How to Play a Macro

Use `@<register>` to play a macro.

Example: `@a` plays the macro in register `a`.

## 🔸 Repeat a Macro

- `@@` — repeat the last executed macro.
- `5@a` — run macro `a` five times.

## 🔸 View Macro Contents

You can view what's stored in a register using the `:reg` command.

```vim
:reg a
```

## 🔸 Save a Macro Permanently

Add the following line in your `.vimrc` to reuse macros across sessions:

```vim
let @a = 'your_macro_content_here'
```

## 🔸 Tips

- Macros are great for repetitive edits.
- You can combine motions, searches, and commands.
- Use with visual selections for complex transformations.

