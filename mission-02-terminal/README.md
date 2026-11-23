# Mission 2 — Terminal and file management
## 1. Mission title
Mission 2 — Become comfortable with the Terminal.

## 2. Task / objective
Practise basic directory, file, flag, pipe, copy, rename, and package-manager operations inside this repository.

## 3. Work completed
Created `terminal-practice/notes.txt`, added two lines, copied it, and renamed the copy to `practice-copy.txt`. Also prepared command and concept notes below.

### Command reference
| Operation / command | What it does | Observation |
|---|---|---|
| `pwd` | Prints the current working directory. | It identifies the location of the shell. |
| `ls` | Lists entries in the current directory. | It shows visible files and folders. |
| `ls -la` | Shows hidden entries and detailed metadata. | It adds permissions, sizes, owners, and timestamps. |
| `cd ..` | Moves to the parent directory. | The shell location changed to the repository's parent folder. |
| `mkdir terminal-practice` | Creates a directory. | A practice directory was created inside Mission 2. |
| `touch notes.txt` | Creates an empty file if it does not exist. | It made the practice file. |
| `cp notes.txt practice-copy.txt` | Copies a file. | The copy retained the original content. |
| `mv practice-copy.txt renamed.txt` | Moves or renames a file. | The file name/path changed. |
| `cat notes.txt` | Displays file contents. | Both practice lines were visible. |

### Safe file practice answers
- Replacing contents rewrites an existing file; appending writes new text after the existing end.
- Copying leaves the original and creates another file. Moving changes the original file's location or name.
- `pwd` provides the absolute location of the shell.
- Directory listing is useful for inspecting files, folders, metadata, and changes before further actions.

### Flags and pipes
Normal `ls` shows names, while `ls -lah` includes hidden entries, detailed permissions and metadata, and human-readable sizes. In `ls -lah | head -n 10`, `ls -lah` produces detailed output and `head -n 10` keeps only the first ten lines. The pipe `|` sends the first command's standard output to the second command.

### Package manager
A package manager helps users install, update, and remove software consistently and track dependencies. Homebrew is commonly used on macOS. This assignment did not install or uninstall packages.

## 4. Commands / tools used
`pwd`, `ls`, `ls -lah`, `cd`, `mkdir`, `touch`, `cp`, `mv`, `cat`, `echo`, and `|`/`head`. The commands were kept inside the assignment repository.

## 5. My understanding
Terminal commands provide direct, repeatable control of files and tools. Flags modify command behavior, and pipes connect command output to another command.

## 6. Difficulties faced
No major difficulties.

## 7. How I resolved them
Not applicable.

## 8. Evidence / files
- `terminal-practice/notes.txt`
- `terminal-practice/practice-copy.txt`

## 9. Commit details
Commit message: **Complete Terminal and file management mission**. The work was pushed to GitHub.
