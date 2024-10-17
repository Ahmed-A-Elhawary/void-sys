# void-sys
dwm and st with my configrautions 

# important file 
  - ~/.xinitrc
    ~/src/dwm/status-script &
    sxhkd &
    dwm
  - .bashrc
      # .bashrc

# If not running interactively, don't do anything
[[ $- != *i* ]] && return

alias ls='ls --color=auto'
PS1='[\u@\h \W]\$ '

# alias for xbps
alias i="doas xbps-install -S"
alias u="i; doas xbps-install -u xbps; doas xbps-install -u"
alias q="doas xbps-query -Rs"
alias r="doas xbps-remove"

# alias for SYS
alias l="ls -l"
alias ll="ls -la"
alias reboot="doas reboot"
alias shut="doas poweroff"
alias shutdown="doas shutdown -P"

# keybord alias
setxkbmap -layout us,ara -variant ,digits -option grp:alt_shift_toggle caps:swapescape

# sys alias
alias mount="doas mount /dev/sda1 /mymount"
alias v="nvim"

- .bash_profile
   startx

  # sound card : sof-hda-dsp and alsa and pipwire and pluseaudio
    try work with alsa and pipwire and learn how to
    work



