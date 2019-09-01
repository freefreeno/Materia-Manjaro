
Materia Manjaro - This is a port of the popular [Materia KDE](https://github.com/PapirusDevelopmentTeam/materia-kde) for Plasma 5 desktop with a few additions and extras. 

In this repository you'll find:
- Three sets of folder icons
- Konsole Color Scheme
- Plasma Color Scheme
- Four Plasma Desktop Themes
- Plasma Look-and-Feel Settings with Splash Screen
- Materia Manjaro GTK Theme made specifically for KDE.
- Kvantum Theme
- Two Aurorae Themes

## Recommendations

- Install Materia Manjaro icons for better looking desktop.

- Set tree menu view for systemsettings

- On systemsettings set **Noto Sans** font for title, menu and toolbar

- For better looking use toolbar icons without text with 16px size (for Papirus themes)

- For Materia Manjaro Blur enable translucency and blur effects on KDE sytemsettings. Set value 6 for blur and 2 for noise strengths on blur effect settings.

- Recommended software for better experience with Materia Blur: Dolphin, Ark, Kate,Falkon, Konsole

## Hacks for small screen resolution

- Install widgets [Active Window Control](https://github.com/kotelnik/plasma-applet-active-window-control) & [Application Menu](https://cgit.kde.org/plasma-workspace.git/tree/applets/appmenu) and move to panel
- Disable window buttons & titlebar on decoration:

open rc-file on aurorae theme and set:
```
ButtonHeight=0
ButtonWidth=0
TitleHeight=0
TitleEdgeTop=0
```
- Use [GTK3-noCSD](https://github.com/PCMan/gtk3-nocsd) script 

## Known issues

- Old version qBittorrent (~3.3.1) not used 22px icon size on toolbar (icons will be blurred, update to fresh version for solve this)

- On some propietary video drivers Aurorae have wrong rendering by default with Materia theme. For fix that use this config on ~/.Xresources:

```
Xft.dpi:       96
Xft.antialias: true
Xft.hinting:   true
Xft.autohint:  false
Xft.hintstyle: hintslight
Xft.lcdfilter: lcddefault
Xft.rgba:      rgb 
```

## Donate

If you like my project, you can donate at:

<span class="paypal"><a href="https://www.paypal.me/freefreeno" title="Donate to this project using Paypal"><img src="https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png" alt="PayPal donate button" /></a></span>


## License

GNU GPL v3

## License for icons

Creative Commons Attribution-NonCommercial-ShareAlike

## Credits go to: Alexey Varfolomeev - https://github.com/PapirusDevelopmentTeam/materia-kde for the orginal Materia-dark theme and many thanks go to him for making such an awesome theme that inspired me to create.

## Wallpaper for theme: Charlie Henson at - https://www.opendesktop.org/u/charlie-henson


## New gradient Aurorae theme is made from the Breezemite Aurorae theme so many thanks goes to them. Original is here https://store.kde.org/p/1169286                                                            https://github.com/andreyorst/Breezemite

