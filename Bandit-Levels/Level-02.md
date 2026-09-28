**File: `bandit-levels/level-02.md`**
```markdown
# Bandit Level 1 → Level 2

## Objective
Read the password stored in a file named `-` located in the home directory.

## Execution
```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220

# Method 1: Explicit relative path
cat ./-

# Method 2: Input redirection
cat < -
