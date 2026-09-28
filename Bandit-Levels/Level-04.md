**File: `bandit-levels/level-04.md`**
```markdown
# Bandit Level 3 → Level 4

## Objective
Find and read the password stored inside a hidden file located within the `inhere` directory.

## Execution
```bash
ssh bandit3@bandit.labs.overthewire.org -p 2220

# Traverse and reveal hidden files
cd inhere
ls -la

# Read the targeted hidden file
cat .hidden
