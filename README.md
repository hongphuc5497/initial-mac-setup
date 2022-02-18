# Initial MacBook Setup

1. Reset to Factory Setting

   - <https://macpaw.com/how-to/factory-reset-macbook>

   - <https://laptopvang.com/cach-reset-macbook/>

2. System References

3. Install Xcode: `sudo xcode-select --install`

4. Install Homebrew: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

5. Install iTerm2: `brew install --cask iterm2`

   - Font: Fira Code

   ```command
    brew tap homebrew/cask-fonts
    brew install --cask font-fira-code
   ```

   - Theme: Atom Theme (Locate in `iterm-color-presets` folder)

6. Install zsh & Oh My Zsh

   - `brew install zsh` (skip this step if zsh is your default shell)

   - `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

   - **References**:

     - <https://www.freecodecamp.org/news/how-to-configure-your-macos-terminal-with-zsh-like-a-pro-c0ab3f3c1156/>

     - <https://dev.to/abdfnx/oh-my-zsh-powerlevel10k-cool-terminal-1no0>

7. Install Node Version Manager (nvm)

   - `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash`

   - `nvm install node`

8. Install yarn: `brew install yarn`

9. Install and configure Git: <https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-config>

10. Install and configure Vim: <https://www.freecodecamp.org/news/vimrc-configuration-guide-customize-your-vim-editor/>

11. Some recommended applications:

    - Visual Studio Code

    - Google Chrome

    - Docker

    - Docker-compose

    - GoTiengViet

    - TablePlus

    - PostgreSQL

    - Redis

    - Elasticsearch

    - Tmux

    - Fig

    - ...

## References

- <https://sourabhbajaj.com/mac-setup/>

- <https://github.com/nicolashery/mac-dev-setup#visual-studio-code>

- <https://betterprogramming.pub/how-to-set-up-your-macbook-for-web-development-in-2021-a7a1f53f6462>
