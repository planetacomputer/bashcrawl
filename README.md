Welcome!

This is a game to teach you the basics of using a POSIX (Linux, BSD, UNIX) terminal.

To start playing, open a terminal.

Type the letters "cd " (just the letters, not the quotes) into the terminal...

Then a space (press the spacebar)...

Then drag and drop the ``entrance`` directory from this folder into your terminal.

If your terminal asks you what you want to do with what you have just dragged into it, select "Paste location".
If it doesn't ask, then expect it to paste the file path of the folder you just dragged into it.

Once you have something like:

```
$ cd /home/your_username/Downloads/bashcrawl/entrance
```

in your terminal window, press RETURN.
The exact path to the entrance varies, depending on where you saved the file.

Your first move is very important.
Type this into your terminal:

```
cat scroll
```

You are now playing the game.
May the gods save you.

## NOTES FOR macOS X
It appears that there is a problem with the standard `Archive Utility` that is called from `Finder` when a zip archive is double-clicked to extract to the current folder, if you're downloading the archive from GitLab rather than using git's `clone` facility to download the game.  You may find that all of the files in the destination folder are set to be executable.  This will cause great confusion as you play the game as intended, because every plain text file will be indistiguishable from executable scripts.  Here's how to avoid this problem:

1.  Open your favorite terminal emulator app (e.g. `Terminal.app` or `iTerm2`).
1.  Navigate to the directory where you want to unpack the zip archive:
    ```
    cd /path/to/destination
    ```
    Replace '/path/to/destination' with the relative (does not start with slash '/') or absolute (starts with slash '/') path to your desired destination.
1.  Type `unzip ` (that's 'unzip' followed by one or more *spaces* [hit the space bar at least once])
1.  From the `Finder`, drag the bashcrawl-master.zip to your terminal emulator window.  The absolute path to your downloaded archive should be pasted into your terminal window similar to the following:
    ```
    unzip /Users/${USER}/Downloads/bashcrawl-master.zip
    ```
1.  Press `Enter` to unpack the contents of the zip archive to the current directory.
1.  In the terminal window change directory to `bashcrawl-master/entrance`:
    ```
    cd bashcrawl-master/entrance
    ```

At this point, you're in the game!  Have fun!
