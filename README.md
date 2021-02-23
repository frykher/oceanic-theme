# oceanic-theme
customized fork of material ocean theme for windows terminal

### Example
![Terminal Goodness](example-theme.png)



## Usage

Copy the contents of `oceanic.json` in the repository or copy from here:

```json
{
  "name": "Oceanic",
  "background": "#0f111a",
  "foreground": "#f1ecec",
  "black": "#000000",
  "blue": "#49baff",
  "brightBlack": "#464b5d",
  "brightBlue": "#49baff",
  "brightCyan": "#3bd3e0",
  "brightGreen": "#16c98d",
  "brightPurple": "#c792ea",
  "brightRed": "#ff5370",
  "brightWhite": "#ffffff",
  "brightYellow": "#ffcb6b",
  "cyan": "#3bd3e0",
  "green": "#16c98d",
  "purple": "#c792ea",
  "red": "#ff5370",
  "white": "#ffffff",
  "yellow": "#ffcb6b"
}
```
1. Go into your Windows Terminal settings
2. Go to "schemes"
3. Paste the theme object into it (make sure you're following the rules of json)
4. Scroll to the shell that you want to use (Powershell, Command Prompt, wsldistros, etc.)
5. Add the "colorScheme" property to it, with its value being "Oceanic"
6. Profit
