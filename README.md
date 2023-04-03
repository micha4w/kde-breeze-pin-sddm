# kde-breeze-pin-sddm
An edited version of the Breeze SDDM/Lock Screen that includes a number pin input.

## Installation
There is not yet an official theme, so you need to patch the theme together manually:
```sh
# as root
mv /usr/share/sddm/themes/breeze/Main.qml /usr/share/sddm/themes/breeze/Main.qml.bac
mv Main.qml /usr/share/sddm/themes/breeze/Main.qml

mv /usr/share/plasma/look-and-feel/org.kde.breeze.desktop/contents/lockscreen/LockScreenUi.qml /usr/share/plasma/look-and-feel/org.kde.breeze.desktop/contents/lockscreen/LockScreenUi.qml.bac
mv LockScreenUi.qml /usr/share/plasma/look-and-feel/org.kde.breeze.desktop/contents/lockscreen/LockScreenUi.qml  
```
