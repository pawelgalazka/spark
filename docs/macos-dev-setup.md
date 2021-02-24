# MacOS dev setup

_Simple guideline to setup node.js development environment_

1. Turn firewall and FileVault (disk encryption)
2. Install password manager (like 1password)

   > https://1password.com

3. Update macOS
4. Install Mac cli tools

```
xcode-select —install
```

5. Install HomeBrew

   > https://brew.sh

6. Install nvm

   > https://github.com/nvm-sh/nvm

7. Pick LTS node version

```
nvm install --lts
nvm use --lts
```

8. Setup Hyper terminal

   > https://hyper.is/

9. Setup terminal add-ons

   > https://github.com/sindresorhus/pure
   > https://github.com/sindresorhus/hyper-snazzy

10. Install git through brew

```
brew install git
```

11. Configure git

```
git config --global user.name "Pawel Galazka"
git config --global user.email "xxx@xxx.com"
git config --global pull.rebase true
git config --global -l
```

12. Setup VSCode

> https://code.visualstudio.com

> To setup `code` command. Press Cmd + Shift + P and then search for "shell command".
> Pick option: "Shell Command: install code command in path"

13. Install essential VSCode extensions

```
code --install-extension dbaeumer.vscode-eslint
code --install-extension esbenp.prettier-vscode
code --install-extension stylelint.vscode-stylelint
```
