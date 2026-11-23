# Mission 3 — Understand the operating system
## 1. Mission title
Mission 3 — Operating systems, processes, storage, paths, and permissions.

## 2. Task / objective
Observe system details safely and explain processes, paths, permissions, and core operating-system responsibilities.

## 3. Work completed
Recorded privacy-safe macOS observations, process examples, path explanations, permission meanings, and an OS responsibility table.

### System information
| Information explored | What it tells you | Privacy-safe observation |
|---|---|---|
| Operating system | Identifies the platform and kernel environment. | macOS, version 27.2.1, Darwin build 26B131 |
| Current account | Identifies the user context allowed to run commands. | Not published; replaced by `[redacted]` |
| Storage | Shows used and available disk space. | Root volume: 926 GiB capacity; approximately 13 GiB used, 224 GiB available at observation time |
| System activity | Provides a snapshot of active processes and resource use. | `launchd` is PID 1; other observed processes include `logd`, `centaurid`, and `smd` |

### Processes
A process is a program or service instance that is currently running. The PID column is the unique process identifier assigned by the OS for the process currently in that namespace. Examples: `launchd` and `logd`.

### Paths and permissions
An absolute path begins at the filesystem root, for example `/Users/[redacted]/.../digital-detective-8531/mission-02-terminal`. A relative path starts from the current directory, for example `../mission-02-terminal/terminal-practice/notes.txt`.

For a text file in the practice area, typical owner permissions are `rw-`: read and write are allowed, while execute is not needed.

| Permission | Meaning | Example |
|---|---|---|
| r | Read | Open and read a text file |
| w | Write | Edit a text file |
| x | Execute | Run a script or traverse a directory |

### OS responsibilities
| Responsibility | Explanation | Example |
|---|---|---|
| Process management | Starts, schedules, pauses, and stops processes. | Switching between applications |
| Memory management | Allocates memory and prevents applications from interfering unnecessarily. | Keeping several apps running |
| Device management | Coordinates hardware through drivers and system services. | Sending text to a monitor |
| File management | Organises and protects files and directories. | Saving and retrieving documents |
| User interface/shell | Provides graphical or command-line interaction. | Finder or Terminal |
| Security and permissions | Controls access to resources and accounts. | Restricting a private file |

## 4. Commands / tools used
`uname`, `sw_vers`, `df -h`, `ps`, `pwd`, `cd`, `ls -l`, and Terminal process views.

## 5. My understanding
The OS is a coordinator: it shares hardware resources among processes and controls where users and applications may read or write.

## 6. Difficulties faced
The storage and process lists contain identifying or frequently changing values.

## 7. How I resolved them
I retained only privacy-safe versions and replaced personal values with `[redacted]`.

## 8. Evidence / files
No screenshots were needed; this README contains privacy-safe observations.

## 9. Commit details
Commit message: **Document operating system and file management**. The work was pushed to GitHub.
