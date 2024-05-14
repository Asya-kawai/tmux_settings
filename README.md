# tmux_settings
This tmux settins is firendly for Emacs users,
and also uses simple status bar and colors.

* Almost keybinding is Emacs like
* Status bar is simpler than others
* Less than 5 colors are used, So it's is easy to eyes
  * Green, White, Blue, Yellow
  
## Custom Keybindings

| KeyBinding | Action |
----|---- 
| Ctrl-t + Ctrl-p | Select the pane above |
| Ctrl-t + Ctrl-n | Select the pane below |
| Ctrl-t + Ctrl-b | Select the pane left |
| Ctrl-t + Ctrl-f | Select the pane right |

| KeyBinding | Action |
----|---- 
| Ctrl-t + j | Join the pane to dst-pane |
| Ctrl-t + J | Join the pane from src-pane |

| KeyBinding | Action |
----|---- 
| Ctrl-t + + | Extend the pane to the top |
| Ctrl-t + - | Extend the pane to the bottom |
| Ctrl-t + < | Extend the pane to the left |
| Ctrl-t + > | Extend the pane to the right |

## Usage

* Put .tmux.conf ~/.

## Install

```
git clone git@github.com:Asya-kawai/tmux_settings.git
cd tmux_settings
cp .tmux_settings ~/.
```
