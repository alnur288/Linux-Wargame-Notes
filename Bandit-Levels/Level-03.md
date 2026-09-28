**File: `bandit-levels/level-03.md`**
```markdown
# Bandit Level 2 → Level 3

## Objective
Retrieve the password stored in a file named `spaces in this filename` in the home directory.

## Execution
```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220

# Method 1: Double-quoting (Recommended)
cat "spaces in this filename"

# Method 2: Backslash escaping
cat spaces\ in\ this\ filename
