# VIM-commands


1.Open Git Bash.

2.Create a script: touch script.sh

3.Edit it: vim script.sh (or use Notepad++)

4.Make it executable: chmod +x script.sh

5.Run it: ./script.sh


Basic Navigation

    h – Move left (←)
    l – Move right (→)
    j – Move down (↓)
    k – Move up (↑)
    gg – Go to the beginning of the file
    G – Go to the end of the file
    0 – Move to the beginning of a line
    ^ – Move to the first non-blank character of a line
    $ – Move to the end of a line
    w – Move to the beginning of the next word
    b – Move to the beginning of the previous word
    Ctrl + d – Move half a page down
    Ctrl + u – Move half a page up

Editing

    i – Insert mode (start typing before the cursor)
    a – Insert mode (start typing after the cursor)
    o – Open a new line below and enter insert mode
    dd – Delete the current line
    x – Delete the character under the cursor
    u – Undo last action
    Ctrl + r – Redo last undone action

Search
    / → search - type key word and then enter
    n - next location of key word

Basic Save and Quit Commands

    :w → Save (write) the file
    :q → Quit (only if no changes were made)
    :wq or :x → Save and quit
    ZZ → Save and quit (same as :wq)

Forcing Save and Quit

    :q! → Quit without saving (force quit)
    :w! → Force save (write the file even if it's read-only)
    :wq! → Force save and quit

Handling Multiple Files

    :wa → Save all open files
    :wqa → Save all files and quit
    :qall! → Quit all files without saving
