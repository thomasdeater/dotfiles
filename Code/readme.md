http://calebporzio.com/my-vs-code-setup-2/

https://burkeknowswords.com/the-greatest-visual-studio-code-setup-in-the-world-22aa30fb8e8f

https://pawelgrzybek.com/sync-vscode-settings-and-snippets-via-dotfiles-on-github/

mv ~/Library/Application\ Support/Code/User/snippets/ ~/.dotfiles/Code/
mv ~/Library/Application\ Support/Code/User/settings.json ~/.dotfiles/Code/
mv ~/Library/Application\ Support/Code/User/keybindings.json ~/.dotfiles/Code/

ln -s /Users/tdeater/.dotfiles/Code/settings.json /Users/tdeater/Library/Application\ Support/Code/User/settings.json
ln -s /Users/tdeater/.dotfiles/Code/keybindings.json /Users/tdeater/Library/Application\ Support/Code/User/keybindings.json
ln -s /Users/tdeater/.dotfiles/Code/snippets/ /Users/tdeater/Library/Application\ Support/Code/User/snippets
