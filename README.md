
---

#### Reverse Shell

```markdown
# Reverse Shell

A Python reverse shell that connects back to a listener for remote command execution.

## Features

- Establishes a reverse TCP connection
- Executes system commands
- Simple and lightweight

## Usage

**Listener (Attacker):**
```bash
nc -lvnp 4444
