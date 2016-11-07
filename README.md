# regdel
Ncurses based interface to ledger: regdel is to ledger what tig is to git.

![animation](/animation.gif?raw=true)

Ledger (http://ledger-cli.org/) is a command line double-entry accounting
system.

Regdel allows to browse your accounts and entries from a ledger file.  I got
the inspiration from the excellent git interface tig
(https://github.com/jonas/tig).

Bug report and patches are welcome.  I only tested it on my own ledger files,
so it might not work very well on other files.

# Commands

- up, k: move up
- down, j: move down
- enter: select
- q: exit/back
- b: show balance view
- x: toggle commodities
- r: toggle --real
