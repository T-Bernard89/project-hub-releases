# Project Hub

Your Claude Code projects on your phone: write to a project, see Claude's replies, answer its questions.

## Install

**Windows:** download `project-hub-windows-setup.cmd` from the [newest release](https://github.com/T-Bernard89/project-hub-releases/releases/latest) and double-click it (if Windows says it protected your PC, choose More info, then Run anyway).
It sets up Ubuntu inside Windows (WSL) and runs the hub there: it asks for permission once and restarts the PC, then carries on by itself, asks for a
Ubuntu user name and password and for the Tailscale and Claude sign-ins, and prints your phone address. Keep the PC from sleeping while you use the hub.

**Linux or Mac:** you need a computer that stays on, with [Claude Code](https://claude.com/claude-code) signed in. For your phone, install
[Tailscale](https://tailscale.com/download) (free) on the computer and the phone and sign in to the same account on both.

1. Download `project-hub-*.tar.gz` from the [newest release](https://github.com/T-Bernard89/project-hub-releases/releases/latest) and unpack it in a folder you will keep (not Downloads): `tar -xzf project-hub-*.tar.gz`
2. Go into the new `project-hub-…` folder and run `./install.sh`. It checks the computer, sets everything up and prints your phone address and a sign-in link.

**Phone:** install [Tailscale](https://tailscale.com/download) and sign in to the same account, open the address, then follow the "Finish setting up" card.
Android: install `project-hub-android-*.apk` from the hub's Settings page (or from the newest release). iPhone or iPad: Share, then Add to Home Screen (on iPad, Share is at the top right).

A Windows PC can also just join a hub on another machine: `install.cmd --join ADDRESS`. Updates install themselves once a day.

**[Download the newest release](https://github.com/T-Bernard89/project-hub-releases/releases/latest)**

Each download has a SHA-256 beside it; installs check it before updating.
