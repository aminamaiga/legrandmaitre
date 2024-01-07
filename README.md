Power shell

Set-ExecutionPolicy Bypass -Scope Process -Force

Set-ExecutionPolicy AllSigned; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

choco install -y nodejs-lts microsoft-openjdk17

https://developer.android.com/studio
