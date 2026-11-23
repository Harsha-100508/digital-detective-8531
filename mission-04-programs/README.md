# Mission 4 — How programs run
## 1. Mission title
Mission 4 — Compilers and interpreters.

## 2. Task / objective
Create and run a simple Python program and compare compiled and interpreted execution.

## 3. Work completed
Created `hello.py`, which prints **Hello from Python**, and compared compiler and interpreter behavior.

| Point | Compiler | Interpreter |
|---|---|---|
| When translation/execution happens | Source is translated before execution. | Instructions are read and executed at runtime. |
| Typical output | A separate executable or intermediate form may be produced. | Direct program behavior or output, often with runtime messages. |
| One example | C/C++ implementations commonly compile source first. | Python commonly executes source through an interpreter implementation. |
| One advantage | Checking can occur before execution and compiled code may run efficiently. | Changes can be tested quickly without a separate build step. |

A compiler translates code into another form before the program starts. An interpreter reads and carries out code while the program runs. Python implementations can involve interpretation plus internal compilation steps, so the difference is conceptual rather than always perfectly separate.

## 4. Commands / tools used
`python3 hello.py` ran the program. Python 3 was used to execute `hello.py`.

## 5. My understanding
Python source is executed through an implementation that interprets bytecode or source and performs runtime operations. This made it clear that output appears only when the program is run.

## 6. Difficulties faced
No major difficulties.

## 7. How I resolved them
Not applicable.

## 8. Evidence / files
- `hello.py`

## 9. Commit details
Commit message: **Compare compilers and interpreters**. The work was pushed to GitHub.
