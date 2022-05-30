Here's a simple-terminal I manually built with some patches added:

- [st-alpha-osc11-20220222-0.8.5.diff](https://st.suckless.org/patches/alpha/)
- [st-anysize-0.8.4.diff](https://st.suckless.org/patches/anysize/)
- [st-boxdraw_v2-0.8.5.diff](https://st.suckless.org/patches/boxdraw/)
- [st-glyph-wide-support-boxdraw-20220411-ef05519.diff](https://st.suckless.org/patches/glyph_wide_support/)
- [st-hidecursor-0.8.3.diff](https://st.suckless.org/patches/hidecursor/)
- [st-scrollback-20210507-4536f46.diff](https://st.suckless.org/patches/scrollback/)
- [st-scrollback-mouse-altscreen-20220127-2c5edf2.diff](https://st.suckless.org/patches/scrollback/)
- [st-undercurl-0.8.4-20210822.diff](https://st.suckless.org/patches/undercurl/)

The terminal's current support for monospaced fonts isn't great, but it's fast. I think I can live with this shortcoming ..

Also I modified the default keys for adjusting fonts:

```
<c-0>: reset font size
<c-->: font size reduction
<c-=>: increase font size

<a-u>: scroll up one line
<a-d>: scroll down one line
<c-a-u>: scroll up one screen
<c-a-d>: scroll down one screen
```
