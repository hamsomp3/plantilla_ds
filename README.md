# Templete DataScience

## Clone the repository

```sh
git clone https://github.com/hamsomp3/plantilla_ds.git
```


# Environment Setup (Requirements)


## Windows Installation
For window users, please install the following packages:

[Chocolatey](https://chocolatey.org/install)



execute the following command in the cmd.exe as administrator to install the packages:

```sh
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

```sh
choco install make
```

```sh
local-setup-windows: install-windows
```

## Unix Installation


```sh
local-setup-mac: install-unix
```