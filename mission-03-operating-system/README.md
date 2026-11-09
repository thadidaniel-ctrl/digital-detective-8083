### Task 3.1 — Exploring my operating system

| Information explored | What it tells you | My observation (privacy-safe) |
|---|---|---|
| Operating system / system details | Which operating system and version my computer is running |My computer runs macOS, version 27.2  |
| Current account identity |which user account I’m logged in as daniel| [redacted] |
| Available and used storage |how much disk space the computer has, how much is used and how much is free  | write the real numbers you see, for example “Size X GB, used Y GB, available Z GB” |
| System activity snapshot |One snapshot of system activity: CPU use, memory use and running tasks|how the time is  the cpu does the work and what are the prioritize the following 
|

### Task 3.2 — Processes

**Command used:** `ps -A -o pid,comm | head -20`

**What is a process?:program in execution

**What does the PID column represent?: a unique id for the process

**Two processes I saw:daniel@daniels-MacBook-Pro ~ % ps -A -o pid,comm | head -20
  PID COMM
    1 /sbin/launchd
  338 /usr/libexec/logd
  341 /usr/libexec/UserEventAgent
  343 /System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/FSEvents.framework/Versions/A/Support/fseventsd
  344 /System/Library/PrivateFrameworks/MediaRemote.framework/Support/mediaremoted
  348 /usr/sbin/systemstats
  352 /usr/libexec/configd
  354 /System/Library/CoreServices/powerd.bundle/powerd
  355 /usr/libexec/IOMFB_bics_daemon
  359 /usr/libexec/remoted
  363 /System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd_system
  365 /usr/libexec/watchdogd
  368 /System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/Metadata.framework/Versions/A/Support/mds
  370 /usr/libexec/kernelmanagerd
  371 /usr/libexec/diskarbitrationd
  374 /usr/libexec/coreduetd
  375 /usr/sbin/syslogd
  377 /usr/libexec/thermalmonitord
  378 /System/Library/PrivateFrameworks/CoreDuetContext.framework/Resources/contextstored
daniel@daniels-MacBook-Pro ~ % 









### Task 3.3 — Paths and permissions

**What I observed when I changed folders:**
When I moved into mission-03-operating-system, the path became  becau/Users/.../digital-detective-8083/mission-03-operating-systemse 
When I ran cd .., the path /Users/.../digital-detective-8083.

**Absolute path vs relative path:**
An absolute path is /Users/[redacted]/digital-detective-8083/mission-02-terminal/terminal-practice/notes.txt. A relative path is mission-02-terminal/terminal-practice/notes.txt.

- Absolute path example: /Users/[redacted]/digital-detective-8083/mission-03-operating-system
- Relative path example: mission-03-operating-system (typed from the project folder)

**Permissions of notes.txt:** (copy the first 10 characters from your ls -l output)

**What the owner can do:**
The owner's letters are w_x This means the owner can can read and execute but cannot not  read .

| Permission | Meaning | Example |
|---|---|---|
| r — Read | you have the permission to read | readind a book online but you cannot edit it  |
| w — Write | you have the permiddion to write | that yoyu can edit the file or document |
| x — Execute | you can execute  the file  | you can execute the file|

