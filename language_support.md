# Language support

PalCode currently supports 6 languages.
All languages, as a minimum, support plain text editing and cloud code execution.

| Language | Syntax highlighting | Auto module installation      | REPL          | Code intelligence | Intelligence for 3rd-party modules | Unit testing |
|----------|---------------------|-------------------------------|---------------|-------------------|------------------------------------|--------------|
| Python   | Yes                 | Yes                           | No            | Yes               | Yes                                | No           |
| Node.JS  | Yes                 | Yes                           | No            | Yes               | No                                 | No           |
| Bash     | Yes                 | Language doesn't have modules | No            | Yes               | Yes                                | No           |
| Java     | Yes                 | No                            | No            | No                | No                                 | No           |
| Golang   | Yes                 | Yes                           | Not supported | No                | No                                 | No           |
| Prolog   | No                  | No                            | Yes           | No                | No                                 | No           |


## What do these mean?
- Syntax highlighting is just the basic colorisation of tokens in your code.
- Auto module installation builds an Abstract Syntax Tree for your code, finds attempts to import 3rd-party packages, and installs them using the language's package manager.
- REPL (Read-Eval-Print Loop) is a piecewise execution environment.
- Code intelligence gives auto-complete suggestions, highlights invalid syntax, and (if applicable) shows type mismatches.
- 3rd-party module code intelligence indexes modules and gives suggestions and error-checking for their exported members and methods.
- Unit testing gives teachers the power to define automated tests for code their students submit.
