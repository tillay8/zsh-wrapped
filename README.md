# zsh-wrapped
spotify wrapped for nerds

A simply program that gives various stats about your terminal history. 

requires bash, zsh, or fish

This operates by scraping your history file. This is located at the following files in each shell:
```
bash - ~/.bash_history
zsh - ~/.zsh_history
fish - ~/.local/share/fish/fish_history
```

to install
```
git clone https://github.com/tillay8/zsh-wrapped
cd zsh-wrapped
python3 wrapped.py
```

needs ZSH or fish shell to get timestamps, bash does not do this. you can still get statistics about commands run, just not the times in bash.

![image](https://github.com/user-attachments/assets/8331f207-0806-4944-a39b-3e6d34ee0842)

modify `wrapped.py` to configure. I made it like a config file so it shouldnt be too hard. Default has all the cool stuff you can do aready that you can change easily
