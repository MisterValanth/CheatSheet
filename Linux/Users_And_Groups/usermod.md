# usermod
The usermod command is a command in Linux that is used to change properties of a user in Linux.
After creating a user it is possible some of the properties need adjustment.
In order to do that we use the usermod command.

Files where user information is stored :

- `/etc/passwd`
- `/etc/group`
- `/etc/shadow`
- `/etc/login.defs`
- `/etc/gshadow`
- `/etc/login.defs`

When using the usermod command, it will make the changes in these files.

:exclamation: usermod command needs to be executed as a root user.

##### Interesting options

| Option                                  | Function                                         |
| --------------------------------------- | ------------------------------------------------ |
| `sudo usermod -c <comment> username`    | adds a comment or short description for the user |
| `sudo usermod -d <directory> username`  | this will change the home directory for the user |
| `sudo usermod -e <YYYY-MM-DD> username` | this will change the expiry date for the user    |
| `sudo usermod -g <group> username`      | this will change group for the user              |
| `sudo usermod -l <username> username`   | this will change login name for the user         |
| `sudo usermod -L  username`             | this will lock the user                          |
| `sudo usermod -U  username`             | this will unlock the user                        |
| `sudo usermod -p <password> username`   | this will set an unencrypt password for the user |
| `sudo usermod -s <path> username`       | this will create a shell for the user            |
| `sudo usermod -u <id> username`         | this will change the id for the user             |

---
Version v1.0


