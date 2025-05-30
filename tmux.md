Ah, got it! You’re asking about must-know tmux shortcuts — not Termux. Here’s a concise list of the essential tmux shortcuts to get you productive fast:

⸻

🧷 Basic tmux Concepts
	•	Prefix key: Ctrl + b (default)
Every tmux shortcut starts with this.

⸻

🚀 Must-Know tmux Shortcuts

Shortcut	Action
Ctrl + b then c	Create new window
Ctrl + b then ,	Rename current window
Ctrl + b then n	Next window
Ctrl + b then p	Previous window
Ctrl + b then &	Close current window
Ctrl + b then "	Split pane horizontally
Ctrl + b then %	Split pane vertically
Ctrl + b then o	Switch to next pane
Ctrl + b then x	Close current pane
Ctrl + b then z	Zoom/unzoom pane
Ctrl + b then :	Enter command mode (e.g. kill-pane)
Ctrl + b then [	Enter scroll mode (use arrow keys to navigate)
Ctrl + b then d	Detach session
tmux attach	Reattach to a session
tmux ls	List tmux sessions


⸻

🔥 Pro Tips
	•	💡 Switch panes using arrow keys:
Ctrl + b then ← / → / ↑ / ↓
	•	🧠 Session management:
	•	tmux new -s mysession – Start new named session
	•	tmux attach -t mysession – Attach to it
	•	tmux kill-session -t mysession – Kill session
	•	🔄 Resizing panes (hold Ctrl + b then press : and type one of):

resize-pane -L 10   # resize left
resize-pane -R 10   # resize right
resize-pane -U 5    # resize up
resize-pane -D 5    # resize down



⸻

Would you like a custom .tmux.conf to improve these bindings or make them more Vim-like?
