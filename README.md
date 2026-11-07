# Project Hub

Your Claude Code projects on your phone: write to a project, see Claude's replies, answer its questions.

## Install

You need a Linux or Mac computer that stays on, with [Claude Code](https://claude.com/claude-code) signed in. For your phone, install
[Tailscale](https://tailscale.com/download) (free) on the computer and the phone and sign in to the same account on both.

1. Download `project-hub-*.tar.gz` from the [newest release](https://github.com/T-Bernard89/project-hub-releases/releases/latest) and unpack it in a folder you will keep (not Downloads): `tar -xzf project-hub-*.tar.gz`
2. Go into the new `project-hub-…` folder and run `./install.sh`. It checks the computer, sets everything up and prints your phone address and a sign-in link.
3. Open the address on your phone and follow the "Finish setting up" card.

Android: after step 3, install `project-hub-android-*.apk` from the hub's Settings page (or from the newest release). iPhone: Share, then Add to Home Screen.
Windows can't run the hub; it can join one (`install.cmd --join ADDRESS`). Updates install themselves once a day.

**[Download the newest release](https://github.com/T-Bernard89/project-hub-releases/releases/latest)**

Each download has a SHA-256 beside it; installs check it before updating.
