# Some requirements for workstation

## Install software and tools

Install required and optional software. Optional for more comfortable work

### Hands-On #00: prepare workspace

1. Install terminal or ssh client.
   1. osx `brew install iterm`
   1. windows `choco install cmder`
   1. linux just work
1. Generate ssh keys - `ssh-keygen`
1. Pass https://vim-adventures.com/ (for free)

### Hands-On #01: prepare to work


1. Kubectl for RHEL7 `yum install kubectl`
1. WARNING: temporary solution for RHEL8
    1. open https://artifactory.raiffeisen.ru and login
    1. Search `kubectl` and copy `url to file`
    1. Download `wget --user <YOUR_USER> --password <url>`
    1. install `sudo rpm -i *.rpm`
1. `sudo yum install helm jq`

**Sudo**
> Используется для получение прав root

**Wget**
> Для загрузки файлов по сети. man wget для подробной информации 


