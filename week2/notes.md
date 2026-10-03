Q1 - pwd command printed the absolute path to the folder I was currently standing in. 
Q2 - ls -a showed the hidden entries . and .., which represent the current directory and its parent directory. Plain ls doesn't show these because it hides 
anything starting with a dot by default.
Q3 - The first column shows the file type and permissions. The d means it's a directory. The next nine characters show permissions in three groups of 
three: the owner can read, write, and execute; the group can read and execute; and everyone else can also only read and execute
Q4 - It worked because coding_cafe/week2 is a relative path, and relative paths are interpreted based on your current location. 
Q5 - mv did two different jobs: first it moved README-backup.md into the week01
   folder without changing its name, then it renamed the file to old-readme.md
   without changing its location. Same command, different result depending on
   the destination path.
Q6 .- 19 folders 
Q7 - python version 3.14
Q8 _ different because she uses different laptop and python is installed at differet location. PATT configurations are different. 
Q9 - Running pyton3 gave "command not found". This happens because the shell
   searches every folder in PATH for a program matching the exact name typed.
   Since pyton3 is misspelled, no folder in PATH contains anything by that
   name, so the search comes up empty.
Q10 - .venv didn't show up with plain ls because ls hides anything starting
    with a dot by default. Just like . and .. earlier, .venv is a hidden
    folder, only visible with ls -a.Qq11 - After activating .venv, my prompt now shows (.venv) at the very beginning,
    before the rest of the prompt text, signaling I'm working inside the
    virtual environment. 
Q12 - Activating the venv adds .venv/bin to the
    front of PATH, so the shell finds this Python first.
q13 - 13. The second pip list included five new packages that weren't in the
    first list: certifi (2026.7.22), charset-normalizer (3.5.1), idna
    (3.19), requests (2.34.2), and urllib3 (2.7.0). Only requests was
    something I directly asked to install — the other four (certifi,
    charset-normalizer, idna, urllib3) were installed automatically
    because requests depends on them to work.
q14 - 14. After running deactivate, which python3 points back to,
    the system Python. deactivate removes .venv/bin from the front of
    PATH, so the shell goes back to finding the system Python first.
q15 - ls -h shows file sizes in a human-readable format, like 1.2K, 3.4M, or
    2.1G, instead of showing the raw number of bytes. It only makes a
    difference when combined with -l, since that's the format that
    displays file sizes in the first place.
q16 - Ctrl+C sent an interrupt signal that cancelled what I was doing but
    kept me inside the Python prompt (>>> was still showing). Ctrl+D
    signaled "end of input," which Python interpreted as a reason to
    exit entirely, taking me back to my normal bash prompt.
