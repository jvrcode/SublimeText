# Sublime Text Cheat Sheet

A quick-reference guide for Sublime Text shortcuts, commands, and tips to speed up your workflow.

## General

| Shortcut | Action |
|---|---|
| `Ctrl + Shift + P` | Command Palette |
| `Ctrl + P` | Quick Open (Go to File) |
| `Ctrl + K, Ctrl + B` | Toggle Sidebar |
| `Ctrl + `` ` | Toggle Console |
| `F11` | Full Screen |
| `Shift + F11` | Distraction-Free Mode |

## Editing

| Shortcut | Action |
|---|---|
| `Ctrl + C` | Copy line (empty selection) |
| `Ctrl + X` | Cut line (empty selection) |
| `Ctrl + Shift + K` | Delete line |
| `Ctrl + Shift + D` | Duplicate line |
| `Ctrl + Shift + Up/Down` | Move line up/down |
| `Ctrl + J` | Join line below |
| `Ctrl + Enter` | Insert line after |
| `Ctrl + Shift + Enter` | Insert line before |
| `Ctrl + /` | Toggle comment |
| `Ctrl + Shift + /` | Toggle block comment |
| `Ctrl + ]` | Indent |
| `Ctrl + [` | Unindent |
| `Ctrl + Shift + V` | Paste with indentation |

## Selection

| Shortcut | Action |
|---|---|
| `Ctrl + D` | Select word (repeat to add next occurrence) |
| `Ctrl + K, Ctrl + D` | Skip current occurrence |
| `Ctrl + Shift + L` | Split selection into lines |
| `Ctrl + L` | Select entire line |
| `Alt + Shift + Up/Down` | Column selection (multi-cursor) |
| `Ctrl + Shift + M` | Select contents of bracket |
| `Ctrl + Shift + A` | Select contents of tag |
| `Ctrl + Alt + Up/Down` | Add cursor above/below |

## Multi-Cursor

| Shortcut | Action |
|---|---|
| `Ctrl + Click` | Add cursor at click point |
| `Ctrl + D` | Add next matching word to selection |
| `Alt + F3` | Select all occurrences of word |
| `Ctrl + Shift + L` | Add cursor to each selected line |

## Find & Replace

| Shortcut | Action |
|---|---|
| `Ctrl + F` | Find |
| `Ctrl + H` | Find and Replace |
| `Ctrl + Shift + F` | Find in Files |
| `F3` | Find Next |
| `Shift + F3` | Find Previous |
| `Alt + Enter` | Select all matches (in Find) |

## Navigation

| Shortcut | Action |
|---|---|
| `Ctrl + P` | Go to File |
| `Ctrl + G` | Go to Line |
| `Ctrl + R` | Go to Symbol |
| `Ctrl + Shift + R` | Go to Symbol in Project |
| `Ctrl + P`, type `@` | Go to Symbol (alternate) |
| `Ctrl + P`, type `#` | Search within file |
| `Ctrl + P`, type `:` | Go to Line (alternate) |
| `Ctrl + M` | Jump to matching bracket |
| `Ctrl + PgUp/PgDn` | Switch tabs |
| `Alt + 1-9` | Switch to tab number |

## Code Folding

| Shortcut | Action |
|---|---|
| `Ctrl + Shift + [` | Fold selection |
| `Ctrl + Shift + ]` | Unfold selection |
| `Ctrl + K, Ctrl + J` | Unfold all |
| `Ctrl + K, Ctrl + 1-9` | Fold to level 1-9 |

## Bookmarks

| Shortcut | Action |
|---|---|
| `Ctrl + F2` | Toggle bookmark |
| `F2` | Next bookmark |
| `Shift + F2` | Previous bookmark |
| `Ctrl + Shift + F2` | Clear all bookmarks |

## Split Panes

| Shortcut | Action |
|---|---|
| `Alt + Shift + 1` | Single pane |
| `Alt + Shift + 2` | Two columns |
| `Alt + Shift + 3` | Three columns |
| `Alt + Shift + 4` | Four columns |
| `Alt + Shift + 5` | Grid (2x2) |
| `Alt + Shift + 8` | Two rows |
| `Alt + Shift + 9` | Three rows |
| `Ctrl + Shift + 1-4` | Move file to group |

## Package Control

| Action | How |
|---|---|
| Install Package Control | `Ctrl + Shift + P` → "Install Package Control" |
| Install a Package | `Ctrl + Shift + P` → "Package Control: Install Package" |
| Remove a Package | `Ctrl + Shift + P` → "Package Control: Remove Package" |
| List Installed Packages | `Ctrl + Shift + P` → "Package Control: List Packages" |

## Popular Packages

| Package | Purpose |
|---|---|
| Emmet | HTML/CSS shorthand expansion |
| SideBarEnhancements | Extended sidebar options |
| SublimeLinter | Linting framework |
| GitGutter | Git diff in gutter |
| A File Icon | File icons in sidebar |
| BracketHighlighter | Bracket/tag matching |
| MarkdownPreview | Render Markdown files |
| Terminal | Open terminal from Sublime |
| ColorPicker | Inline color picker |

## Useful Settings

Add to `Preferences → Settings - User`:

```json
{
    "tab_size": 4,
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "ensure_newline_at_eof_on_save": true,
    "word_wrap": true,
    "highlight_line": true,
    "font_size": 13,
    "rulers": [80, 120],
    "draw_white_space": "selection",
    "save_on_focus_lost": true
}
```

## macOS Users

Replace `Ctrl` with `Cmd` for most shortcuts above.

---

> **Tip:** The Command Palette (`Ctrl + Shift + P`) is your best friend. If you forget any shortcut, just search for the command there.

## License

MIT
