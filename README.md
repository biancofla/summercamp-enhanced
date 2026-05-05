# _Summercamp Enhanced_ 

An enhanced version of the Summercamp theme.

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
