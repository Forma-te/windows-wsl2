1) Se tiver o Docker instalado, remova!

2) Habilite o WSL no Windows 10
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart

3) Habilitar o WSL para a versão 2
wsl --set-default-version 2

4) Instalar o Ubuntu na Microsoft Store

5) Desabilitar o Hyper-v

6) Criar o arquivo .wslconfig em "C:\Users\<seu_usuario>"
[wsl2]
memory=8GB
processors=4
swap=2GB

8) Instalar o Docker

