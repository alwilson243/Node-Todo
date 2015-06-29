Chocolatey:
Run PowerShell as administrator >iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))

choco install nodejs
Example permanently adding node to path
[Environment]::SetEnvironmentVariable("Path", $env:Path + ";C:\Program Files\node", [EnvironmentVariableTarget]::Machine)
http://stackoverflow.com/questions/714877/setting-windows-powershell-path-variable

npm should be in path something like this
C:\Users\Andrew\AppData\Roaming\npm

npm install express@3.4.7 -g


