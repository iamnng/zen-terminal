# Homebrew (MacOS)

Homebrew is a package manager available on MacOS platform that makes it easier to install and update applications and utilities on a Mac. Homebrew installs packages to their own directory and then symlinks their files into `/usr/local` (on macOS Intel) and `/opt/homebrew` (on Apple silicon).

**Homebrew** can install CLI applications and utilities, whereas **Homebrew Cask** extends Homebrew and helps in installation & management of GUI applications, like VS Code and Google Chrome.

Any package/utility/application in Brew terminology is called as **Formula**.

| Action      | Command |
| :---        |    :----   |
| Check if Homebrew is installed | `$ brew --version` <br><br> If Homebrew is installed on your machine, then you will get its version, like - <br> `Homebrew 3.6.20` <br> Otherwise, an error will be printed - <br> `command not found: brew`|
| Install Homebrew | `$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`|
| Update Homebrew | `$ brew update` <br> You should keep Homebrew updated at the latest version before downloading anything |
| Fix the broken links using repair utility | `$ brew doctor`|
| List the formulae installed using Homebrew | `$ brew list`|
| Cleanup and Free Space | `$ brew cleanup`|
| Search if a formula (NVM) is available on Homebrew | `$ brew search nvm` <br> This will show the formulae available on Homebrew as well as on Cask. |
| Install a formula (NVM) | `$ brew install nvm` |
| Uninstall a formula (NVM) | `$ brew uninstall nvm` |
| Upgrade a formula (NVM) | `$ brew upgrade nvm` |
| See what versions of a formula (NVM) is installed | `$ brew list --versions nvm` |

- - -
## Homebrew Repositories

Homebrew third-party repositories can be managed using the `brew tap` command. 

| Action      | Command |
| :---        |    :----   |
| List the currently tapped repositories | `$ brew tap` |
| Add a tap | `$ brew tap <tap-name>` <br> To add a repository `smittytone/homebrew-smittytone`, you'll have to do: <br> `$ brew tap smittytone/homebrew-smittytone`|
| Remove a tap | `$ brew untap <tap-name>` |
- - -