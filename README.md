# Pwndbg + GEF + Peda - One for all, and all for one

This is a script which installs [Pwndbg](https://github.com/pwndbg/pwndbg), [gef](https://github.com/hugsy/gef), [bef](https://github.com/bata24/gef) (bata24's gef) and [Peda GDB](https://github.com/longld/peda) plugins in a single command.

Run `install.sh` and then use one of the commands below to launch the corresponding GDB environment:

```
gdb-peda
gdb-peda-intel
gdb-peda-arm
gdb-pwndbg
gdb-gef
gdb-bef
```

# Installation

```
cd ~ && git clone https://github.com/rand-tech/gdb-peda-pwndbg-gef-bef.git
cd ~/gdb-peda-pwndbg-gef-bef
./install.sh
```

## Update

```
./update.sh
```
