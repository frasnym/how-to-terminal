# How To Terminal
A personal note about how to code in terminal :)

## Create custom command (aliases)

### Ubuntu
1. You will need to edit your `.rc` terminal file
2. For bash: `~/.bashrc`
3. For zsh: `~/.zshrc`
4. Then add this code to create your custom command
```console
alias <NAME>='<CUSTOM_COMMAND>'
# example:
alias back_to_home='cd ~'
```

## Reload your terminal without closing it
- zsh:
```console
exec zsh -l
```
