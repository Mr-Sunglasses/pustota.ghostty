# pustota.ghostty

A clean, minimalist ghostty theme inspired by the original [pustota VSCode theme](https://github.com/sobolevn/pustota). Designed to keep you focused on working in the terminal without visual distractions.

--------------------------------------------------------------------------------
![pustota.ghostty screenshot](https://raw.githubusercontent.com/Mr-Sunglasses/pandora-box/refs/heads/master/Screenshot%20From%202025-07-09%2008-37-39.png)

## Features
- Distraction-free, minimalist aesthetic
- Consistent and calm color palette
- Closely matches the original VSCode Color theme

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Mr-Sunglasses/pustota.ghostty.git
   ```
2. Navigate to the cloned directory:
   ```bash
   cd pustota.ghostty
   ```
3. Copy the `pustota` file to your ghostty themes directory:
    ```bash
    mkdir -p ~/.config/ghostty/themes
    cp pustota ~/.config/ghostty/themes/
    ```
4. List available themes to verify installation:
   ```bash
   ghostty +list-themes
   ```

You should see `pustota` in the list of available themes.

5. Set the theme in your ghostty configuration:
   Edit your `~/.ghostty/config` file and set the theme:
   ```toml
   theme = "pustota"
   ```
6. Restart ghostty to apply the new theme or Reload ghostty config.


--------------------------------------------------------------------------------
Feel free to open an issue or pull request if you notice any missing highlights or inconsistencies. Happy coding!