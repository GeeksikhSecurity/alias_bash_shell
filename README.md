# alias_bash_shell

Sourced from multiple authors
# https://www.learnlinux.tv/linux-essentials-bash-aliases/
# https://gitlab.com/dwt1/dotfiles/-/blob/master/.bashrc

# set them up in your .bashrc config file.
nano ~/.bashrc

# All you have to do is simply copy and paste the aliases into a section within this file, and then every terminal you open will automatically have the aliases you’ve created available.

# some more ls aliases
alias ll='ls -l'
alias la='ls -A'
alias l='ls -CF'
alias l="ls -lh"
alias cpu5='ps auxf | sort -nr -k 3 | head -5'
alias speedtest='curl -s https://raw.githubusercontent.com/sivel/speedtest-cli/master/speedtest.py | python -'
alias upgrade='sudo apt update && sudo apt dist-upgrade'
alias i='sudo apt install'
alias lsmount='mount |column -t'
alias diskfree='df -h -x squashfs -x tmpfs -x devtmpfs'


