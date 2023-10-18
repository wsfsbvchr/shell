# shell
A collection of shell scripts

## System level
### dummybrowser
This script is used as a custom default web browser. Instead of a random click potentially opening an actual web browser, the URL provided to the script is copied to clipboard by xsel and also stored in a log file for convenience.
### dummymailer
This script is used as a custom default email client. Instead of a random click potentially opening an actual email client, the URL provided to the script is copied to clipboard by xsel and also stored in a log file for convenience.
### pidgin-clipboard
This script is basically the same as dummybrowser, except it's specifically for use with Pidgin, and has a different logfile. It also used to have slightly different behaviour in the past, but not right now.

## Archives
### stripextension
A helper script that returns file name without the extension.

The following are intended to be registered to your file manager's context menu.
### extractall
This script is a wrapper for xarchiver, which extracts selected archives to current directory, into directories named after the archive. There's a very basic logging functionality.
### extractall_to
This script is a wrapper for xarchiver, which extracts selected archives to a specified location, into directories named after the archive. There's a very basic logging functionality.
### extractall_tmp
This script is a wrapper for xarchiver, which extracts selected archives to a temporary directory, into directories named after the archive. There's a very basic logging functionality.
