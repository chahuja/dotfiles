# Cheatsheet
* A collection of all the commands and personalized scripts on this workstation

## Processes
* htop

## Dual Monitors
* arandr - gui
* xrandr - commandline

## ~/scripts/
* atlas-login : remote login to workstation and servers
* new-project : Creates a folder tree for a new project based on a model
  - Usage - `new-project <project-name>`
  - ```sh
  project-name
		├── dataset/
		├── notes/
		├── papers/
		├── src/
		└── README
	```
* rsync-gdrive : uses rsync to maintain a backup copy on the remote server
* youtube-music : uses youtube-dl to download music from a given list of URLs

## useful programs
* alias : list all the aliases

## Python Dependency tree
* sfood or snakefood
  - sfood path2project | sfood-graph | dot -Tps > out.eps

## Tmux
* Save session and restore
  - `prefix + C-s` - save session
  - `prefix + C-r` - restore session

* Copy and paste
  - `prefix + y` - copies text from the command line to clipboard.
  - `prefix + Y` (shift-y) - copy pane current working directory to clipboard.

* Copy mode bindings:
  - `y` - copy selection to system clipboard
  - `Y` (shift-y) - "put" selection - equivalent to copying a selection, and
  pasting it to the command line

* Synchronize panes - used to type the same commands in all the panes
  - `prefix + :setw synchronize-panes`

## Take Screenshots
* `gnome-screenshot`
   - `-a` for custom area
   - `-w` for a window