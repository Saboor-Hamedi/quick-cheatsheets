# These are my persona notes

- To move data from Ubunut into windows
  . scp saboor@192.168.80.128:/home/saboor/report.txt "D:/Hacking"
- This S-- is not allowed in alexxxle moves from Ubuntu into windows. saboor@192.168.80.128 is my vmware ip address

- To move from Windows into Ubuntu
  . iscp -r "D:/Hacking/" saboor@192.168.80.128:/home/saboor/

### To install nvim latest version

```
sudo add-apt-repository ppa:neovim-ppa/unstable
sudo apt update

```

### Install Neovim

```
sudo apt install neovim
```

# Verify

nvim --version

### Ubuntu run terminal in the middle of screen

```bash
gsettings set org.gnome.mutter center-new-windows true

```

### To remove it

```bash
gsettings set org.gnome.mutter center-new-windows false
```

- To find folders on Ubuntu
  `bash find /usr/ -name fonts`

### Best aliases:

- Here are my top aliases for windows 11. These are my favourite.

```
alias no="cd /c/Users/Saboor/AppData/Local/nvim"
alias load="source ~/.bashrc"
alias bashrc="vim ~/.bashrc"
alias dsk="cd ~/oneDrive/Desktop"
# source C:/Users/Saboor/miniconda3/Scripts/activate base
alias home="cd ~"
alias vim="nvim"
alias cc="clear"
alias remove="rm -rf"
alias go='cd'
# Open my notes from everywhere.
alias notes="vim D:/notes.md"
# Sets standard user prompt
if [[ $EUID -ne 0 ]]; then
    PS1="\[\e[1;32m\]\u 🔐 \[\e[1;34m\]\w \[\e[0m\]"
# Sets root user prompt in bright red
else
    PS1="\[\e[1;31m\]\u 🔐 \[\e[1;34m\]\w \# \[\e[0m\]"
fi
eval "$(oh-my-posh init bash --config ~/oh_my_posh.json)"

```
