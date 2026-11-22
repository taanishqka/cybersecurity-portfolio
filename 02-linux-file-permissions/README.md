# Linux File Permissions and Access Control

## Project Overview
This project focuses on managing file and directory permissions in a Linux environment. The objective was to review existing permissions and modify them according to the organization's security requirements.

## Objectives
- Inspect file and directory permissions.
- Understand user, group, and other permission levels.
- Modify permissions using Linux commands.
- Restrict unauthorized write and execute access.
- Improve basic file access security.

## Tools Used
- Linux Terminal
- Linux command-line utilities

## Tasks Performed

### 1. Checked File and Directory Details
Used the `ls -la` command to list files, directories, hidden files, and their existing permissions.

### 2. Changed File Permissions
Used the following command to remove write permission for others:

```bash
chmod o-w project_k.txt
```

### 3. Modified Hidden File Permissions
Modified permissions for the hidden file `.project_x.txt`:

```bash
chmod u-w,g-w,g+r .project_x.txt
```

This removed write permissions from the user and group and added read permission to the group.

### 4. Changed Directory Permissions
Used the following command to remove execute permission from the group for the `drafts` directory:

```bash
chmod g-x drafts
```

## Key Learnings
- Understanding Linux file permission structures.
- Identifying read, write, and execute permissions.
- Understanding user, group, and other access levels.
- Using `chmod` to modify file and directory permissions.
- Recognizing hidden files in Linux.
- Applying basic access control principles.

## Conclusion
Through this activity, I gained practical experience in Linux file permission management and access control. I learned how to inspect existing permissions and modify them to meet specified security requirements.

## Activity Evidence
The original portfolio activity document containing terminal screenshots and explanations is included in this repository.
