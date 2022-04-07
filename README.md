# SHvmm
SHvmm is a QEMU Virtual Machine Manager written in a purely POSIX Compliant Shell Script.

## Configuration
Like any sensible program, the configuration files are located in `$HOME/.config`, and the configuration setup can be run at anytime by running SHvmm with the `--setup` flag

## Usage
```bash
./shvmm --help
./shvmm --setup
./shvmm --create
./shvmm --start [VM Name]
./shvmm --delete [VM Name]
```

## License
SHvmm is licensed under the GNU General Public License, version 2.0
