# py-vm

Simple CLI wrapper for VirtualBox. Could be considered a Vagrant replacement in many cases.

Usage:

```
  vm create <name> <type> <cpus> <mem_mb> <disk_mb> <iso_path>
  vm types
  vm list
  vm start <name>
  vm stop <name>
  vm vnc <name>
  vm ssh <name>
  vm ssh-copy-id <name>
  vm change-ports <name>
  vm eject-disk <name>
  vm delete <name>
  vm rename <src> <dst>
  vm clone <src> <dst>
  vm export <name> <file.ova>
  vm import <name> <file.ova>
```

For proper bash completion add to your ~/.bashrc:

```
complete -W 'create types list start stop vnc ssh ssh-copy-id change-ports '\
'eject-disk delete rename clone export import' vm
```

Reddit discussion: [https://redd.it/5ab2th](https://redd.it/5ab2th).
