<h1 align="center">Vitesse Theme for Windows Terminal (Unofficial)</h1>

An unofficial version of [antfu/vscode-theme-vitesse](https://github.com/antfu/vscode-theme-vitesse) designed for Windows Terminal. 🎨

This theme is inspired by the colors of the Vitesse VSCode theme, with some modifications to ensure proper functionality in Windows Terminal.

![Preview](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/screenshots/dark-soft.png?raw=true)

### Available Schemes:
- [x] [Vitesse Dark Soft](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/dark-soft.json)
- [x] [Vitesse Light Soft](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/light-soft.json)
- [x] [Vitesse Dark](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/dark.json)
- [x] [Vitesse Black](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/black.json)
- [x] [Vitesse Light](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/light.json)

# Installation

### Option 1: Add to Your Current Configuration
1. Download and open the `.json` file of your preferred scheme (e.g., `dark-soft.json`).
2. Open Windows Terminal settings and click **Open JSON file** at the bottom left corner.
   ![Open JSON file](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/screenshots/openJson.png?raw=true)
3. Locate the `schemes` block in the opened JSON file.
4. Copy the contents of the theme’s `.json` file and paste it inside the `[]` in the `schemes` block. If it’s not the first scheme, make sure to add a comma before it.
5. Save the file and restart Windows Terminal. Then open Windows Terminal settings again.
6. Go to **Your Profile or Defaults** > **Appearance** > **Color Scheme** and select the installed theme.
7. Enjoy your new theme!

### Option 2: Replace the Configuration
> [!WARNING]
> This will overwrite your Windows Terminal configuration!

1. Download and open [`settings.json`](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/settings.json).
2. Open Windows Terminal settings and click **Open JSON file** at the bottom left corner.
   ![Open JSON file](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/screenshots/openJson.png?raw=true)
3. Replace the current Windows Terminal configuration with the downloaded `settings.json`.
4. Go to **Your Profile or Defaults** > **Appearance** > **Color Scheme** and choose your preferred theme.
5. Enjoy your new theme!
