# WindowsHelloPINRemover
Removes Windows Hello PIN if you stuck with it and can't change it or remove it yourself
# Disclaimer
Using Windows will become little bit harder after deleting the PIN, it will ask you to do it on every restart, until i find a cure for it just use it on ur own risk.
# Usage
Just run .bat file as administator
# Commands to use instead of bat file:
takeown /f C:\Windows\ServiceProfiles\LocalService\AppData\Local\Microsoft\NGC /r /d y

icacls C:\Windows\ServiceProfiles\LocalService\AppData\Local\Microsoft\NGC /grant administrators:F /t

**open** "C:\Windows\ServiceProfiles\LocalService\AppData\Local\Microsoft\NGC" **and delete everything from it**

**restart pc**
