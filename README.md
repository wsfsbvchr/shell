# shell
A collection of shell scripts, grouped by intended use.

Some scripts have requirements, most commonly something like GNU coreutils or the util-linux package. Rarer requirements are mentioned.

---

## System level
### dummybrowser
This script is used as a custom default web browser. Instead of a random click potentially opening an actual web browser, the URL provided to the script is copied to clipboard by xsel and also stored in a log file for convenience. Requires xsel.
### dummymailer
This script is used as a custom default email client. Instead of a random click potentially opening an actual email client, the URL provided to the script is copied to clipboard by xsel and also stored in a log file for convenience. Requires xsel.
### pidgin-clipboard
This script is basically the same as dummybrowser, except it's specifically for use with Pidgin, and has a different logfile. It also used to have slightly different behaviour in the past, but not right now. Requires xsel.
### stripextension
A helper script that returns file name without the extension.

---

## Archives
The following are intended to be registered to your file manager's context menu.
### extractall
This script is a wrapper for xarchiver, which extracts selected archives to current directory, into directories named after the archive.
### extractall_to
This script is a wrapper for xarchiver, which extracts selected archives to a specified location, into directories named after the archive. Requires zenity.
### extractall_tmp
This script is a wrapper for xarchiver, which extracts selected archives to a temporary directory, into directories named after the archive.

---

## streamlink
The following are wrappers for [streamlink](https://github.com/streamlink/streamlink).
### hlsmpv
This script initiates streamlink and opens mpv for the stream.
### twitchmpv
This script initiates streamlink and opens mpv. Specifically crafted for Twitch VODs.
### twitchhls
Another variant which uses doesn't force the use of mpv.

---

## random
### webcam
Uses fswebcam to capture an image through V4L2 and /dev/video0. Tuned for an old webcam of mine, highly adjustable.
