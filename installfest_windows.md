# Java Installfest (Windows)

## Git & GitHub

- [Create a new account](https://git-invite.generalassemb.ly/invite) to access GitHub Enterprise
- Post the GitHub username you just created into our Slack channel 
- [Download and install Git Bash](https://gitforwindows.org/)

### Git Proxy Configuration

Run these commands in Git Bash (it doesn’t matter where, you’re updating a global Git setting):
```
git config --global user.name "YOUR NAME HERE"
git config --global user.email YOUR_EMAIL@DOMAIN.COM

git config --global https.proxy [TBD]
git config --global http.proxy [TBD]
git config --global http.sslVerify false
```

> You can verify the settings you entered with `git config --list`

## Java SE Development Kit 11

[Download and install Java JDK (Version 11)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)

## PostgreSQL

[Download and install PostgreSQL (version > 9.5)](https://www.postgresql.org/download/windows/)

## IntelliJ IDEA

[Download and install IntelliJ IDEA Ultimate](https://www.jetbrains.com/idea/download/#section=windows)
