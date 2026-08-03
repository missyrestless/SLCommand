# Second Life Bash Scripts

Convenience scripts for Second Life. These are primarily Bash scripts,
command line utilities to be run in a terminal session.

Supported environments are Unix/Linux &amp; Mac. These might run on Microsoft
Windows System for Linux (WSL) but they are untested in that environment.

## Contents

- [firestorm.sh](https://github.com/missyrestless/SLCommand/blob/main/firestorm.sh)
  - Execute the Firestorm viewer from the command line
  - Linux &amp; Mac
  - Firestorm viewer
- [view_chat.sh](https://github.com/missyrestless/SLCommand/blob/main/view_chat.sh)
  - View and search chat history
  - Linux &amp; Mac
  - Firestorm viewer

## Requirements

- Unix/Linux or Mac operating system
- Terminal session
- Bash
- User with `sudo` privilege

## Installation

One line install:

```bash
curl -fsSL https://raw.githubusercontent.com/missyrestless/SLCommand/refs/heads/main/install | bash
```

Alternatively, clone this repository and execute the `install` script:

```bash
git clone https://github.com/missyrestless/SLCommand.git
cd SLCommand
./install
```
## Setup execution path

Add `/usr/local/bin` to your `PATH` environment variable:

```bash
export PATH="/usr/local/bin:${PATH}"
```

## Usage and Help

To view usage help for most utilities included here
use the `-h` command line option. For example:

```bash
view_chat -h
firestorm -h
```

## Updates

Updates can be performed with:

```bash
cd /path/to/SLCommand
git pull
./install
```

## Feedback and Support

Email `missyrestless@gmail.com` with questions, comments, suggestions, or issues.
