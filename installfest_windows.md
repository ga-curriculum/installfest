# Java Installfest

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

## AdoptOpenJDK 

Run `java -version` on the Windows cmd prompt. If the JDK version is 1.8 or higher, don't install OpenJDK. 

[Download and install AdoptOpenJDK (Version 8, JVM OpenJ9)](https://adoptopenjdk.net/?variant=openjdk8&jvmVariant=openj9)

