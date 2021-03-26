<h2 align="center">Dash Scripts</h2>

---

<h4>colour/pick</h4>

Pick a colour from screen and copy it to the clipboard system.

- Dependencies: 
  + imagemagick
  + xclip : https://github.com/Jack12816/colorpicker
  + colorpicker
  + libnotify ; notify-send

<img align="right" src="/_docs/pick.png">

--

<h4>screenhot/fullscreen</h4>

Copy the fullscreen to clipboard.

- Dependencies:
  + imagemagick
  + libnotify ; notify-send
  + unclutter (optional, just delete the lines that use it)

<img align="right" src="/_docs/fullscreen.png">

---

<h4>screenhot/screen</h4>

Copy the fullscreen to clipboard.

- Dependencies:
  + imagemagick
  + libnotify ; notify-send
  + unclutter (optional, just delete the lines that use it)

<img align="right" src="/_docs/screen.png">

---

<h4>root/doasedit</h4>

Edit a file  from root using **doas** and `$EDITOR` local user configuration, script made by @AN322. Thank you.


- Dependencies:
  + doas

<img align="right" src="/_docs/doasedit.png">

---

<h4>emojis/loademoji</h4>

Load kaomoji from a simple file.

- Dependencies:
  + dmenu
  + xdotool
  + libnotify ; notify-send
  + xclip

<img align="right" src="/_docs/loademoji.png">

---

<h3>lemonbar</h3>

<img src="/_docs/topbar.png">
<img src="/_docs/botbar.png">

There are two lemonbars, one at the bottom and other at the top, both use multiple scripts that are well documented in each script, please give a look if you want to just take one without the entire lemonbar, which is normally what I do.

I do have a **.md** file explaining a little bit of how this whole script was born, but it's not complete yet.

- Dependencies:
  + dash
  + xorg
  + xdotools
  + tuxi
  + sensors
  + lm_sensors ; sensors
  + libnotify ; notify-send
  + mpd
    * mpc
  + dwm
    * dwm-msg

- Todo:
  + Redirect all colours to a single files for fast switch theming