# _Summercamp Enhanced_ 

A warmer, clearer take on **Summercamp** theme.

## Why

The original Summercamp theme looks great, but some text can feel too low-contrast during daily use. _Summercamp Enhanced_ is meant to feel like the same theme, just easier to read for longer sessions.

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/biancofla/summercamp-enhanced.git
   ```

2. **Install it in Zed**

   Open Zed and run `zed: extensions` from the command palette, then choose **Install Dev Extension** and select the cloned `summercamp-enhanced` folder.

3. **Select the theme**

   Choose:

   ```text
   Summercamp Enhanced
   ```

## Manual Installation

If you prefer, copy the theme file directly:

```bash
cp themes/summercamp-enhanced.json ~/.config/zed/themes/
```

Then set it in `~/.config/zed/settings.json`:

```jsonc
{
  "theme": {
    "mode": "dark",
    "dark": "Summercamp Enhanced"
  }
}
```

## What Changed

| Area | Token | Original | Enhanced | What it improves |
| --- | --- | --- | --- | --- |
| Editor | `editor.background` | `#1b1810` | `#17140d` | A slightly deeper canvas for better contrast |
| Editor | `editor.foreground` | `#f8f5de` | `#fff8dc` | Brighter main text |
| UI | `text.muted` | `#736e55` | `#aaa37f` | Secondary text is easier to read |
| UI | `text.placeholder` | `#4c4735` | `#9b9475` | Placeholders no longer fade away |
| Gutter | `editor.line_number` | `#676559` | `#9b9475` | Line numbers stay visible without taking over |
| Gutter | `editor.active_line_number` | `#e3e2de` | `#fff8dc` | The current line is easier to spot |
| Editor | `editor.active_line.background` | `#231f16bf` | `#211d15cc` | A clearer active line with less visual weight |
| Syntax | `syntax.comment` | `#777159` | `#9b9475` + italic | Comments are readable, but still secondary |
| Syntax | `syntax.comment.doc` | `#777159` | `#aaa37f` + italic | Documentation comments get a little more presence |
| Syntax | `syntax.punctuation` | `#bfbb9b` | `#d4cda8` | Delimiters and brackets are easier to parse |
| Syntax | `syntax.keyword` | `#499bef` | `#6db4ff` | Keywords keep their blue accent with more clarity |
| Syntax | `syntax.function` | `#f1fe28` | `#f6ff5c` | The neon yellow survives, just brighter |
| Syntax | `syntax.string` | `#faa11c` | `#ffb84a` | Strings feel warmer and more legible |
| Syntax | `syntax.number`, `boolean`, `constant` | `#5dea5a` | `#76f27a` | Literals keep the neon green, with better contrast |
| Syntax | `syntax.type` | `#5aeabb` | `#72f0c8` | Types are easier to distinguish |
| Syntax | `syntax.predictive` | `#78434a` | `#bb8b76` + italic | Ghost text is visible without looking like real code |
| Terminal | `terminal.background` | `#1b1810` | `#17140d` | Terminal and editor feel consistent |
| Terminal | `terminal.dim_foreground` | `#1b1810` | `#9b9475` | Dimmed terminal text remains readable |
| Terminal | `terminal.ansi.bright_red` | `#7f2724` | `#ff6a5c` | Bright red is actually bright |
| Terminal | `terminal.ansi.bright_green` | `#28842c` | `#79f27d` | Success output is easier to see |
| Terminal | `terminal.ansi.bright_blue` | `#234b7f` | `#8fc2ff` | Bright blue no longer looks muted |
| Terminal | `terminal.ansi.bright_magenta` | `#88487e` | `#ffacef` | Magenta gets proper contrast |
| Terminal | `terminal.ansi.bright_cyan` | `#288461` | `#8bf8d5` | Cyan is clearer in terminal output |

## Troubleshooting

If the theme does not show up after installing it as a dev extension, restart Zed and make sure you selected the folder that contains `extension.toml`.

For manual installs, check that the file is here:

```text
~/.config/zed/themes/summercamp-enhanced.json
```

and that your settings use the exact theme name:

```jsonc
"dark": "Summercamp Enhanced"
```
