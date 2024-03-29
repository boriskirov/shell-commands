# shell-commands
A list of command line operations for working. I use `zsh` for my daily work.

### Basic
Configuring user information used across all local repositories

| Command      | Description |  Example | 
| :---        |    :----   |  :----   |
| `cd`    |  changes the directory of the command line path      | `cd <path/to/directory>` |
| `ls`    |  lists the contents of a directory.        | `ls <path/to/directory>` |
| `open`    |  configure repo only author name for all your commits  | `open "filename"` |
| `cp`    |  copy a file to another directory        | `cp "filename <path/to/directory>"`|
| `mv`    |  move a file to another directory        | `mv "filename <path/to/directory>"`|
| `mv`    |  rename a file or a directory        | `mv "old-file-name" "new-file-name"`|
| `mkdir`    |  create a directory        | `mkdir "directoryname"`|
| `q`    |  quit the sub-screen and return back to terminal        | |
| `clear`    | clear the terminal screen        | |
| `ifconfig`    | display all the active interfaces details, also checks the assigned IP address of an server.        | |
| `esc`    |  escape        | |
| `:wq`    |  write & escape        | |

### Oh My Zsh
[Oh My Zsh](https://ohmyz.sh/) framework for managing my Zsh configuration

### Plugins
Plugins are third-party scripts or applications that extend the functionality of an application. Use plugins to customize your experience, or create more efficient workflows.

| Plugin      | Shorcut |  Description | 
| :---        |    :----   | :----   |
| [z - jump around](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/z)   |  z <name>    | This plugin defines the z command that tracks your most visited directories and allows you to access them with very few keystrokes. |
| [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#manual-git-clone)   |  just do it    | This plugin suggests commands as you type based on history and completions. |
  | [web-search](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/web-search)   |  ddg "search-query"    | This plugin adds aliases for searching with DuckDuckGo, Google, Wiki, Bing, YouTube and other popular services. |


How my plugin list looks like:
`plugins=(git nvm z ssh-agent zsh-autosuggestions web-search)`
