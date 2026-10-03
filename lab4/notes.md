Q1 - --global saves the setting in a file in my home folder 
(~/.gitconfig), so it applies to every repository on my Mac. If I left it 
out, Git would save the setting only in the current repository, and other 
projects wouldn't see it.

Q2 - ls lists only the visible files and folders. ls -a (the a is for 
"all") also lists hidden ones, meaning anything whose name starts with a 
dot.The hidden folder is .git. It stores the project's history and 
settings.

Q3 - About 5 items. .DS_Store was the one I didn't write, because macOS 
creates it

Q4 - .DS_Store disappeared and .gitignore appeared.

Q5 - It should be committed, so anyone who clones the repo gets the same 
ignore rules.
