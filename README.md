# Hyprland login theme for SDDM

This theme was based of off the fantastic sddm theme Sugar-Dark (https://github.com/MarianArlt/sddm-sugar-dark)

### Dependencies

[`sddm >= 0.18.0`](https://github.com/sddm/sddm), [`qt5 >= 5.11.0`](http://doc.qt.io/qt-5/index.html), [`qt5-quickcontrols2 >= 5.11.0`](http://doc.qt.io/qt-5/qtquickcontrols2-index.html), [`qt5-svg >= 5.11.0`](https://doc.qt.io/qt-5/qtsvg-index.html)

*Make sure these are up to date!*

###### From other desktop environments

[Download the tar archive from openDesktop](https://www.opendesktop.org/p/1272122) and extract the contents to the theme directory of SDDM *(change the path for the downloaded file if necessary)*:
```
$ sudo tar -xzvf ~/Downloads/hyprsddm.tar.gz -C /usr/share/sddm/themes
```
This will extract all the files to a folder called "hyprsddm" inside of the themes directory of SDDM.  

After that you will have to point SDDM to the new theme by editing its config file, preferrably at `/etc/sddm.conf.d/sddm.conf` *(create if necessary)*. You can take the default config file of SDDM as a reference: `/etc/sddm.conf/usr/lib/sddm/sddm.conf.d/sddm.conf`.  

In the `[Theme]` section simply add the themes name: `Current=hyprsddm`. Also see the [Arch wiki on SDDM](https://wiki.archlinux.org/index.php/SDDM).
