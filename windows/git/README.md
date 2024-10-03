# Git Config Files

## [git-prompt.sh](/windows/git/git-prompt.sh)

The `git-prompt.sh` file is a script that enhances the command-line experience when working with Git repositories. It provides customizable and informative displays in the terminal, indicating the current repository state. This script, often used with Bash, shows details like the active branch, uncommitted changes, untracked files, and more. It can also incorporate visual cues such as icons or colors to highlight different aspects. Overall, `git-prompt.sh` enhances Git's command-line interface by visually presenting essential repository information for a more convenient and informative workflow.

### git-prompt.sh Location

```shell
~\.config\git\
```

## [.bash_profile](/windows/git/.bash_profile) and [.bashrc](/windows/git/.bashrc)

The `.bash_profile` and `.bashrc` files are configuration files used by the Bash shell in Unix-like systems to customize the command-line environment.

- **.bash_profile**: This file is executed when you log in to your account. It's commonly used to set environment variables, customize paths, and run commands that should execute once at the start of the session. It can also be used to establish global preferences for your terminal session.

- **.bashrc**: This file is executed every time you open a new terminal or terminal window. It's useful for defining command aliases, adjusting the appearance of the prompt, and setting other terminal-specific configurations. Changes made in `.bashrc` apply to the current terminal session.

Regarding the `history -a` option, this command in the Bash configuration files is used to persist the command history to a file called `.bash_history`. This ensures that the commands you entered in the terminal are recorded even after you close the session, allowing you to access previous commands in future sessions.

In summary, `.bash_profile` runs when logging in and is suitable for global configurations, while `.bashrc` runs when opening a terminal and is ideal for terminal-specific settings. The `history -a` option helps store command history for later access.

### .bash_profile and .bashrc Location

```shell
~\
```
