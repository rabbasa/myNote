# myNote

 export HISTSIZE=5000
 source ~/.git-completion.bash
 source ~/.git-prompt.sh
 source ~/.bash_color
 PATH=$PATH:/usr/local/mysql/bin:~/bin
 export CLICOLOR=1
 export LSCOLORS=ExFxBxDxCxegedabagacad
 alias ls='ls -GFh'
 alias gl='git h'
 alias gh='git h'
 export  PS1="\n\[$BWhite\]=======================================================================================\n\[$BWhite\]\d \t      \[$Blue\]jobs:\j      \[$BRed\]hist:\!      \033[33;1m\w \n\033[36m\u\033[m@\033[32mmba $(__git_ps1 "(\033[36m%s\033[33;1m)")\033[m\$ "
