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


1. 
2.