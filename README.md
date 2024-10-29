### This repository is currently being used for backups. Please see here: [https://ppa.floorp.one/](https://ppa.floorp.app/)

Currently, this repository is being used for backup and may not be working properly as a PPA.
Floorp repository for Ubuntu.

## Usage

Just run the following command!
```
$ curl -fsSL https://Floorp-Projects.github.io/Floorp-PPA/KEY.gpg | sudo gpg --dearmor -o /usr/share/keyrings/Floorp.gpg
$ sudo curl -sS --compressed -o /etc/apt/sources.list.d/Floorp.list "https://Floorp-Projects.github.io/Floorp-PPA/Floorp.list"
$ sudo apt update
$ sudo apt install floorp
```
