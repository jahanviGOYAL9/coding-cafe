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

Q6 - README.md moved from "Untracked files" to "Changes to be committed". 
git add moved it from the working directory into the staging area, but it 
isn't in the repository until I commit.

Q7 - After the commit, Git printed [main (root-commit) 027ce20] Lab work 
so far.8 files were changed. 

Q8 - The first seven characters of a commit (027ce20 for yours) are the 
short commit hash, the start of the commit's long unique ID. They're used 
to refer to that exact commit, for example to look at it later or go back 
to it, and seven characters is usually enough to tell it apart from every 
other commit.

Q9 - 1	Check what changed (git status)
2. Stage the file (git add)
3. Commit it (git commit)
4. Look at the history (git log --oneline)

Q10- README.md has a special name and place because GitHub 
automatically shows it on the repository's front page. It's the first 
thing a visitor sees, so it explains what the project is and who made it.

Q11 - gh auth login logged me in to GitHub through the browser and saved 
an access token on my computer. It also set up Git to use that token, so 
when I push, Git proves who I am automatically and never asks for a 
password.

Q12 - The front page shows my README.md, with my name, roll number and 
contents list. GitHub displays it automatically because it's named 
README.md and sits in the main folder.

Q13 - Pushing did not change my local history. The same three commits are 
there, but now there's an origin/main label next to the latest one, 
showing GitHub is up to date with my laptop.

Q14 - A private repository still exists on GitHub's servers, but only I 
and the people I invite, like my TAs, can see it. If the repository didn't 
exist on GitHub, my work would only be on my laptop, so nobody else could 
view it and I'd have no backup.
