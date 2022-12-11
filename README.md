# WindowsHelloPINRemover
Removes Windows Hello PIN if you stuck with it and can't change it or remove it yourself
# Usage
Just run .bat file as administator
# Commands to use instead of bat file:
takeown /f C:\Windows\ServiceProfiles\LocalService\AppData\Local\Microsoft\NGC /r /d y

icacls C:\Windows\ServiceProfiles\LocalService\AppData\Local\Microsoft\NGC /grant administrators:F /t

**open** "C:\Windows\ServiceProfiles\LocalService\AppData\Local\Microsoft\NGC" **and delete everything from it**

**restart pc**
