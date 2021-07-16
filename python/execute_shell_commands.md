# How to execute shell commands

```python
import os
os.system("command")
```

- system - function to execute shell commands
- command - command you want to execute

## Example

```python
import os
os.system("ls -al")
```

```bash
list of files and folders
```

other_way: use subprocess to run commands (recommended)

```python
import subprocess
subprocess.call(["ls", "-al"])
```

- call - function that execute command and options
