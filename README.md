# Configuration Installation

## Windows 

```
rmdir /s /q %APPDATA%\Code\User\
git clone git@github.com:TyOverby/vscode-config.git %APPDATA%\Code\User
```

## OS-X

```
rm -rf "$HOME/Library/Application Support/Code/User"
git clone git@github.com:TyOverby/vscode-config.git "$HOME/Library/Application Support/Code/User"
```

# Linux 

```
rm -rf $HOME/.config/Code/User
git clone git@github.com:TyOverby/vscode-config.git $HOME/.config/Code/User
```

# Plugin Installation

```
code --install-extension vscodevim.vim --install-extension ms-vscode.csharp --install-extension rust-lang.rust --install-extension ms-vscode.cpptools
```
