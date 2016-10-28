# py-vm

Simple CLI wrapper for VirtualBox.

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
