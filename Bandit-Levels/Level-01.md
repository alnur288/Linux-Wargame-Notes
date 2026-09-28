# Bandit Level 0 → Level 1

## Objective
Log into the game server via SSH and locate the password stored in a file named `readme` in the home directory.

## Execution
```bash
# Connect to the remote server on the specified port
ssh bandit0@bandit.labs.overthewire.org -p 2220

# List contents and read the file
ls -la
cat readme
