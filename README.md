# cordova-sqlite-ext dependencies

AUTHOR: Christopher J. Brody

LICENSE: Unlicense (public domain)

Contains source and object code built from:
- SQLite3 (public domain)
- Android-sqlite-native-driver-regexp-pcre (Unlicense, public domain)
- Android-sqlite-connector (Unlicense, public domain)
- sqlite3-pcre (public domain) from git.altlinux.org/people/at/packages/?p=sqlite3-pcre.git - thanks to https://github.com/ralight/sqlite3-pcre for the link
- PCRE 8.37 (BSD 3-clause)

This project provides the following dependencies needed by cordova-sqlite-ext:
- `sqlite3.h`, `sqlite3.c` - SQLite `3.8.10.2` amalgamation needed to build iOS and Windows versions
- `libs` - Android-sqlite-connector JAR and Android-sqlite-native-driver NDK libraries built with SQLite `3.8.10.2` amalgamation
