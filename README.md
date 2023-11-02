# xenonlinux
# internsctl - Custom Linux Command

[![Version](https://img.shields.io/badge/version-v0.1.0-blue.svg)]()

`internsctl` is a custom Linux command designed for various system operations, providing a convenient interface for common tasks. It includes commands to gather CPU and memory information, manage users, and retrieve details about files.

## Usage

### Options:

- `--help`: Display help information and examples.
- `--version`: Display the version of the command.

### Commands:

- `cpu getinfo`: Display CPU information.
- `memory getinfo`: Display memory information.
- `user create <username>`: Create a new user with login access.
- `user list`: List all regular users.
- `user list --sudo-only`: List all users with sudo permissions.
- `file getinfo <file-name>`: Get information about a file.
- `file getinfo --size <file-name>`: Get the size of a file.
- `file getinfo --permissions <file-name>`: Get file permissions.
- `file getinfo --owner <file-name>`: Get the owner of a file.
- `file getinfo --last-modified <file-name>`: Get last modified time of a file.

### Examples:

```bash
internsctl cpu getinfo
internsctl memory getinfo
internsctl user create john
internsctl user list
internsctl user list --sudo-only
internsctl file getinfo hello.txt
internsctl file getinfo --size hello.txt
internsctl file getinfo --permissions hello.txt
internsctl file getinfo --owner hello.txt
internsctl file getinfo --last-modified hello.txt
