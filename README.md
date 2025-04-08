<h1 align="center">Apple Classical</h1>
<p align="center"><strong>A packaged version of Apple Classical macOS version using Pake.</strong></p>

## Releases

Apple Classical
<a href="https://github.com/vinchibana/Classical/releases/download/v1.0/Classical.dmg">Mac</a>

![Classical.jpg](https://s2.loli.net/2025/04/03/SngYWwtTG7D2x6z.jpg)
<br/>

## Shortcuts reference

<br/>

| Mac                         | Windows/Linux                  | Function                      |
| --------------------------- | ------------------------------ | ----------------------------- |
| <kbd>⌘</kbd> + <kbd>[</kbd> | <kbd>Ctrl</kbd> + <kbd>←</kbd> | Return to the previous page   |
| <kbd>⌘</kbd> + <kbd>]</kbd> | <kbd>Ctrl</kbd> + <kbd>→</kbd> | Go to the next page           |
| <kbd>⌘</kbd> + <kbd>↑</kbd> | <kbd>Ctrl</kbd> + <kbd>↑</kbd> | Auto scroll to top of page    |
| <kbd>⌘</kbd> + <kbd>↓</kbd> | <kbd>Ctrl</kbd> + <kbd>↓</kbd> | Auto scroll to bottom of page |
| <kbd>⌘</kbd> + <kbd>r</kbd> | <kbd>Ctrl</kbd> + <kbd>r</kbd> | Refresh Page                  |
| <kbd>⌘</kbd> + <kbd>w</kbd> | <kbd>Ctrl</kbd> + <kbd>w</kbd> | Hide window, not quite        |
| <kbd>⌘</kbd> + <kbd>-</kbd> | <kbd>Ctrl</kbd> + <kbd>-</kbd> | Zoom out the page             |
| <kbd>⌘</kbd> + <kbd>+</kbd> | <kbd>Ctrl</kbd> + <kbd>+</kbd> | Zoom in the page              |
| <kbd>⌘</kbd> + <kbd>=</kbd> | <kbd>Ctrl</kbd> + <kbd>=</kbd> | Zoom in the Page              |
| <kbd>⌘</kbd> + <kbd>0</kbd> | <kbd>Ctrl</kbd> + <kbd>0</kbd> | Reset the page zoom           |

In addition, double-click the title bar to switch to full-screen mode. For Mac users, you can also use the gesture to go to the previous or next page and drag the title bar to move the window.


## Command-Line Packaging

```bash
pake https://classical.music.apple.com/us --name Classical --dark-mode true --
icon <path>

