# DOS Player

A web page for playing your own copy of an old DOS game (such as Race Mania) in the browser, using [js-dos](https://js-dos.com) (DOSBox compiled to WebAssembly).

**Open it:** https://mariuspaukste.github.io/dos/

- Choose the game as a `.zip` or `.rar` (or pick the folder on desktop). Everything is unpacked and run on your device; nothing is uploaded.
- The page lists the game's programs and picks the most likely one to start.
- **Automatic CD setup:** many CD games refuse to start without their disc. The page searches the game's settings files for the path it expects (for example `C:\RACEMANI\`) and sets up a matching CD drive. A `.cue`/`.iso` image in the archive is used as the CD. You can also choose the CD setup by hand.
- Can keep the game and its save files on the device (IndexedDB).
- On-screen buttons on phones: arrows, Ctrl, Alt, Space, Enter, Esc, Y, N.
- "Technical details" shows the DOSBox start-up commands and the files found, for troubleshooting.

No game files are included in this repo.
