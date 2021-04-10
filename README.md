# st - simple terminal

st is a simple terminal emulator for X which sucks less.

# Patches

- [boxdraw](https://st.suckless.org/patches/boxdraw/)
- [font2](https://st.suckless.org/patches/font2/)
- [ligatures](https://st.suckless.org/patches/ligatures/)
- [scrollback](https://st.suckless.org/patches/scrollback/)
- [anysize](https://st.suckless.org/patches/anysize/)

# Requirements
- Xlib header files to build st.
- [Iosevka font](https://typeof.net/Iosevka/)
- [FiraCode Mono Nerd Font](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/FiraCode) (optional)

# Installation
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

```sh
chmod +x install.sh && ./install.sh
```

# Running st
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

# Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

