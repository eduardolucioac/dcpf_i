dcpf_i
======

Script for delete tracks using keyboard shortcuts in Amarok.  Is a change in "dcpf-0.1.8" script. On track deletion the tracklist proceed to  the next track instead of returning to previous. Returns to the first track when  we delete the last in the tracklist.

Install:
-----

With Amarok closed go to ...

```
~/.kde/share/apps/amarok
```

... create "scripts" folder if it does not already exists;

Copy the folder "dcpf-0.1.8" in "scripts" one;

Open Amarok and go "Settings" -> "Configure Amarok..." -> "Scripts", locate
"Delete Current Playing File", enable it, click "Apply" and "OK";

After this, under "Settings" menu will be available the "Delete current playing file..." shortcut;

 * Create a keyboard shortcut to the "Delete Current Playing File" script in Amarok:

Follow "Settings" -> "Configure Shortcuts..." -> "Amarok", locate
"Delete current playing file..." set the keyboard shortcut you want and click "OK";
