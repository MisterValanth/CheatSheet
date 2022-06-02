# ls
The ls command is used to list files or directories in Linux (or other Unix-based operating systems).
Just like you navigate in your File explorer or Finder, the ls command allows you to list all files or directories in the current directory by default.

The ls command also accepts flags/options which are additional information that changes how files or directories are listed.

`ls [flags] [directory]`

`ls`
Base command to list all files and directories of the current working directory.

| Option           | Function                                                                                     |
| ---------------- | ---------------------------------------------------------------------------------------------|
| `ls [directory]` | list contents of the specified directory                                                     |
| `ls /`           | list contents under root directory                                                           |
| `ls ..`          | list contents of the parent directory                                                        |
| `ls ../..`       | list contents of the parent directory 2 levels above                                         |
| `ls ~`           | list contents of the user home directory                                                     |
| `ls -d */`       | list only directories                                                                        |
| `ls *`           | list contents of directory with it's subdirectories                                          |
| `ls -R`          | list all files and directories with their corresponding subdirectories down to the last file | 
| `ls -s`          | list all files with their size (kb). Use -sh for human readable format                       |
| `ls -lh`         | list all files in long format. Permissions, links, owner, group, size, modified, name        |
| `ls -a`          | list all hidden files (.filename)                                                            |
| `ls -(r)t`       | list files ordered by (reverse) date                                                         |
| `ls -S(r)`       | list files ordered by size (reverse)                                                         |   
| `ls > output.txt`| print the output of the ls command to an output file                                         |

On a linux server information can be found by executing `man ls`.


---
Version v1.1
