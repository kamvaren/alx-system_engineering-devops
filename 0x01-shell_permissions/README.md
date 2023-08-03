# Shell Permissions Project
This project contains several shell scripts that demonstrate various file and directory permission operations in Linux. Each script is located in its corresponding task directory.

## Task 0: My name is Betty

The script `0-iam_betty` switches the current user to the user "betty" using the `su` command.

## Task 1: Who am I

The script `1-who_am_i` prints the effective username of the current user using the `whoami` command.

## Task 2: Groups

The script `2-groups` prints all the groups that the current user is a member of using the `groups` command.

## Task 3: New owner

The script `3-new_owner` changes the owner of the file "hello" to the user "betty" using the `chown` command.

## Task 4: Empty!

The script `4-empty` creates an empty file called "hello" using the `touch` command.

## Task 5: Execute

The script `5-execute` adds execute permission to the owner of the file "hello" using the `chmod` command.

## Task 6: Multiple permissions

The script `6-multiple_permissions` adds execute permission to the owner and group, and read permission to others for the file "hello" using the `chmod` command.

## Task 7: Everybody!

The script `7-everybody` adds execute permission to all users (owner, group, and others) for the file "hello" using the `chmod` command.

## Task 8: James Bond

The script `8-James_Bond` sets the file permissions of "hello" to no permission for all (owner, group, and others), then adds read, write, and execute permissions to others using the `chmod` command.

## Task 9: John Doe

The script `9-John_Doe` sets the file permissions of "hello" to read, write, and execute for the owner, and execute only for the group and others using the `chmod` command.

## Task 10: Look in the mirror

The script `10-mirror_permissions` sets the file permissions of "hello" to be the same as the file "olleh" using the `chmod` command.

## Task 11: Directories

The script `11-directories_permissions` adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users using the `find` and `chmod` commands.

## Task 12: More directories

The script `12-directory_permissions` creates a new directory called "my_dir" in the current directory with permissions 751 using the `mkdir` command.

## Task 13: Change group

The script `13-change_group` changes the group owner of the file "hello" to the group "school" using the `chgrp` command with elevated privileges (`sudo`).

