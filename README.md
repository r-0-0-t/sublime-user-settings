**_This folder should be located at ~/.config/sublime-text-3/Packages/User_**

**_Remove the existing User folder with these_**

### Font not included in here but installed in system -

> Operator Mono

### Fix Package Dependencies:

```console
$ sudo npm install --global prettier
$ sudo gem install rufo
```

### Tweaks for Operator Mono:

> Open **_Material Theme_** with **_Resource Viewer_** [CTRL + Shift + P > Resource Viewer > Open Resource > Material Theme].
> Then open **_schemes>YOUR_CURRENT_THEME.mTheme_**.

> Add this few lines

```html
<!--  Operator Tweaks -->
<dict>
  <key>name</key>
  <string>Italic HTML attribute names</string>
  <key>scope</key>
  <string
    >entity.other.attribute-name, entity.other.attribute-name.html,
    entity.other.attribute-name.event.html, entity.other.attribute-name.id.html,
    entity.other.attribute-name.class.html, ,
    entity.other.attribute-name.tag.jade, constant.other.symbol.ruby</string
  >
  <key>settings</key>
  <dict>
    <key>foreground</key>
    <string>#ff9e6a</string>
    <key>fontStyle</key>
    <string>italic</string>
  </dict>
</dict>
<!-- End Operator Tweaks -->
```
