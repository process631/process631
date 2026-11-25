# Security-focused software developer

Security tooling and applications, written to be scoped, testable, and conservative in what they touch. Public work covers authorized reconnaissance and network scanning, Windows system hygiene, and secure development for Windows and Android / React Native.

All security tooling is for authorized testing and education only.

```
$ ps -o pid,stat,cmd
  PID STAT CMD
  631 S    recon --authorized
  631 S    hygiene --disk --process
  631 S    build --windows --android
```

## Focus

- Network reconnaissance and enumeration
- Secure application development
- System hardening and disk / process hygiene tooling
- Automation with Bash

## Selected projects

| Project | Description |
| --- | --- |
| [web-recon-tools](https://github.com/process631/web-recon-tools) | Bash scripts for passive and active reconnaissance on authorized lab targets: HTTP metadata collection, security-header snapshots, and conservative nmap scans of common web ports. |
| [DiskSweeper](https://github.com/process631/DiskSweeper) | A Windows app that shows what is using disk space and safely deletes junk, leftovers, and installed programs, with a command-line tool and automated tests. |
| [forkcast](https://github.com/process631/forkcast) | A TypeScript / React web app that helps choose a recipe and walks through cooking it step by step. |

## Tools

Bash · nmap · curl · C# / .NET · WPF · TypeScript · React · Vite · Node.js · GitHub Actions
