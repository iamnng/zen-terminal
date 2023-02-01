# Homebrew (MacOS)

Homebrew is a package manager available on MacOS platform that makes it easier to install and update applications and utilities on a Mac. Homebrew installs packages to their own directory and then symlinks their files into `/usr/local` (on macOS Intel) and `/opt/homebrew` (on Apple silicon).

Homebrew can install CLI applications and utilities, whereas Homebrew Cask extends Homebrew and helps in installation & management of GUI applications, like VS Code and Google Chrome.

Any package/utility/application in Brew terminology is called as **Formula**.

| Action      | Command |
| :---        |    :----   |
| Check if Homebrew is installed | `$ brew --version` <br><br> If Homebrew is installed on your machine, then you will get its version, like - <br> `Homebrew 3.6.20` <br> Otherwise, an error will be printed - <br> `command not found: brew`|
| Install Homebrew | `$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`|
| Update Homebrew | `$ brew update` <br> You should keep Homebrew updated at the latest version before downloading anything |
| List the formulae installed using Homebrew | `$ brew list`|
| Search if a formula (Node) is available on Homebrew | `$ brew search node` |
| Install a formula (Node) | `$ brew install node` |