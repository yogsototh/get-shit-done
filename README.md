# Get Shit Done

This small script is inspired by:

[`https://github.com/leftnode/get-shit-done`](https://github.com/leftnode/get-shit-done.git) by [leftnode](https://github.com/leftnode/).

Only it is written in `zsh` and should work also on Mac. Yeah, PHP sucks for this kind of work.

# How to Install?

1. Open Terminal
2. git clone https://github.com/leftnode/get-shit-done.git .
3. cd get-shit-done
4. sudo ./get-shit-done work
5. Harden the fuck up
6. sudo ./get-shit-done play
7. ???
8. Profit

Good Work!

# Annoyed by password?

Edit `/etc/sudoers` by using `sudo visudo`.
**At the end** of the file add:

    userName ALL=(ALL) NOPASSWD: /path/to/get-shit-done
