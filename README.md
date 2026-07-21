# Linux Commands Documentation

## Overview

This repository documents my hands-on journey of learning Linux commands using Windows Subsystem for Linux (WSL). Every command included in this repository has been executed, tested, and documented with explanations, examples, terminal output, and screenshots.

The goal of this project is to build a solid foundation in Linux while maintaining professional documentation that demonstrates both practical skills and understanding.

## 📚 Command Library

This repository is organized into sections, with each section covering a specific area of Linux. Every command includes its purpose, syntax, examples, real-world use cases, screenshots, and key takeaways.

## 🎯 Who This Repository Is For

- Aspiring DevOps Engineers
- Cloud Engineers
- Linux Beginners
- KCNA Candidates
- Azure Administrators

## 📋 Prerequisites

Before using this repository, you should have:

- A Linux environment (Ubuntu, WSL, or a Linux VM)
- Basic familiarity with the terminal
- A text editor such as VS Code (optional)
- Git installed (recommended for following along)

### Verify Your Environment

Run the following commands to confirm your setup:

```bash
uname -a
git --version
bash --version
```

_If the commands return version information, you're ready to begin_.

### 📁 01. Navigation Commands
- [`pwd`](01-navigation/README.md) — Display the current working directory.
- [`ls`](01-navigation/README.md) — List files and directories.
- [`cd`](01-navigation/README.md) — Change the current working directory.

### 📁 02. File Management
- [`mkdir`](02-file-management/README.md) — Create directories.
- [`touch`](02-file-management/README.md) — Create empty files.
- [`cp`](02-file-management/README.md) — Copy files and directories.
- [`mv`](02-file-management/README.md) — Move or rename files and directories.
- [`rm`](02-file-management/README.md) — Remove files and directories.
- [`cat`](02-file-management/README.md) — Display file contents.
- [`less`](02-file-management/README.md) — View file contents one page at a time.
- [`head`](02-file-management/README.md) — Display the beginning of a file.
- [`tail`](02-file-management/README.md) — Display the end of a file.

### 📁 03. Sorting & Text Processing
- [`wc`](03-sorting-processing/README.md) — Count lines, words, and bytes.
- [`sort`](03-sorting-processing/README.md) — Sort text alphabetically or numerically.
- [`uniq`](03-sorting-processing/README.md) — Remove duplicate lines.
- [`cut`](03-sorting-processing/README.md) — Extract specific columns or fields from text.
- [`tr`](03-sorting-processing/README.md) — Translate or replace characters. 
- [`tee`](03-sorting-processing/README.md) — Write output to both the terminal and a file. 

## 📂 04. Searching & Filtering

- [`find`](04-searching-filtering/README.md) — Search for files and directories.
- [`locate`](04-searching-filtering/README.md) — Find files quickly using a database.
- [`grep`](04-searching-filtering/README.md) — Search for text patterns in files.
- [`which`](04-searching-filtering/README.md) — Locate the executable of a command.
- [`whereis`](04-searching-filtering/README.md) — Find a command's binary, source, and manual pages.

---
### 🚧 Coming Soon

- **05. Permissions** — `chmod`, `chown`, `umask`
- **06. System Information** — `whoami`, `hostname`, `uname`, `df`, `du`, `free`, `uptime`
- **07. Process Management** — `ps`, `top`, `kill`, `pkill`, `jobs`, `bg`, `fg`
- **08. Archives & Compression** — `tar`, `gzip`, `gunzip`, `zip`, `unzip`
- **09. Networking** — `ping`, `curl`, `wget`, `ip`, `ss`, `netstat`

---

**Progress:** **23 commands documented** 
