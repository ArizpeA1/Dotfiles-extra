# Dotfiles-extra
Own dotfiles should help sometime
# Requirements.
- Pulseaudio (for the audioup and down)
- x server (.xinitrc)
- urxvt terminal

# Instalation
Install dwm or what you wm you prefer (My latest build of dwm is in the tar file, should be configured with everything)

    git clone https://github.com/ArizpeA1/Dotfiles-extra.git
    
Get on the folder and copy what you need.

    cp .xinitrc /home/(Your-user-goes-here)/
    cp .Xresources /home/(Your-user-goes-here)/
    
For installing the audio files:

    ln -s audioup /usr/local/bin/audioup
    ln -s audiodown /usr/local/bin/audiodown
    
You're done
    
# Vim

    tar xf vim.tar.gz  /home/(Your-user-goes-here)/.vim
    cp .vimrc /home/(Your-user-goes-here)/.vimrc
    
 That's it for vim dotfiles deployment
