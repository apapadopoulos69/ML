Steps to run:
1) Create shortcut of "Winmine__XP.exe"
2) On "Winmine__XP.exe - Shortcut" right click -> Properties -> Shortcut tab -> on Run select 'Maximized'
3) Double click on shortcut (should open as a maximized window)
4) Open project's location on cmd and run the script as "python3 MinesweeperQAgent.py", will load the latest Q-table at
392.000 games and will not play randomly (run the cmd on bottom right of the screen or on a separate monitor because the
script clicks to set the game's window active).
WHILE script is running:
- Don't move the mouse.
- Don't press anything.
- A table will be saved every 500 episodes/games around 200MB as a pkl file, takes 10-15 minutes.

5) hold 'q' on keyboard to cancel running

Alternatively:
- follow the same instructions to run "python 3 MinesweeperDQAgent.py"
- set predict = False, to play randomly by epsilon
- set load = False, to not load any model
- load any other table by setting its name by the requested game




