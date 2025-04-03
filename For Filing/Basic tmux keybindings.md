---

---

Tmux provides several keybindings to execute commands quickly in a tmux session. Here are some of the most useful ones.

First, create a new tmux session if you're not already in one. You can name your session by passing the parameter `-s {name}` to the `tmux new` command when creating a new session:

```shell
$ tmux new -s Session1
```

- **Ctrl+B D** — Detach from the current session.
- **Ctrl+B %** — Split the window into two panes horizontally.
- **Ctrl+B "** — Split the window into two panes vertically.
- **Ctrl+B Arrow Key** (Left, Right, Up, Down) — Move between panes.
- **Ctrl+B X** — Close pane.
- **Ctrl+B C** — Create a new window.
- **Ctrl+B N** or **P** — Move to the next or previous window.
- **Ctrl+B 0 (1,2...)** — Move to a specific window by number.
- **Ctrl+B :** — Enter the command line to type commands. Tab completion is available.
- **Ctrl+B ?** — View all keybindings. Press **Q** to exit.
- **Ctrl+B W** — Open a panel to navigate across windows in multiple sessions.

For additional keybindings, consult the tmux man pages.