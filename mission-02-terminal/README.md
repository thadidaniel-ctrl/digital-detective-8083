### Task 2.1 — Basic Terminal operations

| Operation | Command | What it does | What I observed |
|---|---|---|---|
| Current-directory display | `pwd` |it shows me the current path  |i see the path where i am |
| Directory listing | `ls` |it shows what is the inside the folder|i observe the listing of the files if in a folder |
| Detailed listing | `ls -l` |it shows detailed listing |I see the permissions of owner other |
| Change directory | `cd ..` |this help us take one step towards the home directory  |i am going one step towards |
| Create directory | `mkdir terminal-practice` | this creates a directory |the directory is created  |
| Create empty file | `touch original.txt` | this creates the an file |it creates the file   |
| Copy file | `cp original.txt copy.txt` |this copies the file   |it copies the file  |
| Move / rename file | `mv copy.txt renamed.txt` |this moves or renames the file   |  |
| Display file contents | `cat original.txt` |displays the contents of the file |itshows the content that are present in the file|





### Task 2.3 — Flags and pipes

| Command | What changed compared to plain `ls` |
|---|---|
| `ls` |it shows the listing and gives us the overview of what is inside the folder|
| `ls -l` |this shows the listing in long format   |
| `ls -a` |this shows the hiden files and folders  |
| `ls -lah` |this is the combination of all the 2 command above  |
| `ls -l \| head -3` |this shows the first 3 lines of the  listing as it is piped  |

**What the pipe does:**
the pipe take the output of the left command and gives it to the right command 

**Left side of the pipe contributes:**
the output of the left command it taken and it is given as input to the right command 




### Task 2.4 — Package managers

**Commands run:** `brew --version`, `brew list`

**What I observed:Homebrew 7.0.11, and. for the second command we  see all the the packages installed by the hembrew

**Why package managers are useful (2-3 sentences):
A package manager is a tool that installs, updates and removes software for you, from the Terminal. Instead of downloading installers from websites, you type one command and it handles the download, the setup and the extra files the software needs.