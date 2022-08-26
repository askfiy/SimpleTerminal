Here's a simple-terminal I manually built with some patches added:

- [st-alpha-osc11-20220222-0.8.5.diff](https://st.suckless.org/patches/alpha/)
- [st-anysize-0.8.4.diff](https://st.suckless.org/patches/anysize/)
- [st-boxdraw_v2-0.8.5.diff](https://st.suckless.org/patches/boxdraw/)
- [st-glyph-wide-support-boxdraw-20220411-ef05519.diff](https://st.suckless.org/patches/glyph_wide_support/)
- [st-hidecursor-0.8.3.diff](https://st.suckless.org/patches/hidecursor/)
- [st-scrollback-20210507-4536f46.diff](https://st.suckless.org/patches/scrollback/)
- [st-scrollback-mouse-altscreen-20220127-2c5edf2.diff](https://st.suckless.org/patches/scrollback/)
- [st-undercurl-0.8.4-20210822.diff](https://st.suckless.org/patches/undercurl/)
- [st-font2-20190416-ba72400.diff](https://st.suckless.org/patches/font2/)
- [st-charoffsets-20220311-0.8.5.dif](https://st.suckless.org/patches/charoffsets/)
- [st-nobadweight-20220308-4b53196.diff](https://st.suckless.org/patches/nobadweight/)

If you need to add an icon to the terminal, execute the following command:

```
sudo wget -P /usr/local/share/pixmaps/ https://st.suckless.org/patches/netwmicon/st.png
```

Also I modified the default keys for adjusting fonts:

```
<c-0>: reset font size
<c-->: font size reduction
<c-=>: increase font size

<a-u>: scroll up 5 line
<a-d>: scroll down 5 line
<c-a-u>: scroll up one screen
<tc-a-d>: scroll down one screen
```

Please download some dependent fonts:

```
yay -S ttf-recursive
yay -S archlinuxcn/nerd-fonts-go
```

Simple-terminal does not support some monospaced fonts very well, so it is normal when encountering font problems (cjk).

But the above two fonts are used perfectly.

