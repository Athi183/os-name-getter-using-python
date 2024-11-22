# os-name-getter-using-python


```markdown
# System Information Script

This Python script prints basic information about the operating system using the `os` and `platform` modules.


## How It Works
- **`os.name`**: Prints the name of the operating system module in use (e.g., `posix`, `nt`).
- **`platform.system()`**: Prints the name of the operating system (e.g., `Linux`, `Windows`, `Darwin`).
- **`platform.release()`**: Prints the release version of the operating system.

### Example Output
On a Linux system:
```
posix
Linux
5.15.0-60-generic
```

On a Windows system:
```
nt
Windows
10
```

## Applications
- Identify the operating system for debugging or cross-platform compatibility.
- Log system details in your Python applications.

## License
This script is open-source and available under the MIT License.
```
