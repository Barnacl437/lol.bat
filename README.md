# lol.bat
A (more like two's) simple recursive Windows Batch file that opens itself when triggered. Just for fun.

I wrote this when I was playing with the Windows 8.1 VM. Abusing its low RAM amount, I wanted to torture it a bit.
If you want this to open an eternity of CMD windows and seeing, you can write this yourself and even better (this repo is useless though.)

Now this repo has two files, `lol.bat` and `l0l-alt.bat`. The second is an alternative written from scratch based on the original .bat, with modified/appended codes to control the CMD pop-up speed. I recommend this, as it's easier for you to kill it ASAP. The first probably if you want to benchmark an unused/test PC.

![image](https://user-images.githubusercontent.com/87983017/204020251-7c403130-4ffd-47cf-9d81-c4dfda5f45fb.png)

*Warning: this seems perfectly for a troll but do it with care. It may affect system stability by using a lot of system memory and can eventually crash it. You have to be able to stop this by ending `cmd.exe` process tree in Task Manager's Details tab or just end the process at Processes tab. It will be fun only if you can control the fun.*
*Update: fortunately, this troll is tested relatively safe and you can just hold-spamming Alt-F4 on the CMD windows, they will be closed, without other windows appearing.*
