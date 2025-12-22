# Linux File Permissions – Security Project

##  Project Overview
This project demonstrates how I managed file and directory permissions in Linux to improve system security.

The objective was to ensure that users only had the access level required for their role, following the principle of least privilege.

I used common Linux command-line tools to inspect, understand, and modify permissions inside a projects directory.


## Checking Existing Permissions
I started by reviewing the current permissions of files and directories using:

bash
  ## ls -la

This command displays:
hidden files
file ownership
detailed permission settings
From the output, I identified:
regular files
a hidden file
a subdirectory named drafts
Each file showed a 10-character permission string that defines access rights.
