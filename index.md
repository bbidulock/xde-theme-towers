---
layout: default
---
[xde-theme-towers -- read me first file.  2021-12-08]: #

xde-theme-towers
===============

Package `xde-theme-towers-1.2` was released under CCPL:cc-by-nc-nd-3.0
license 2021-12-08.

This is a theme and a set of backgrounds for the _XDE (X Desktop
Environment)_ that provides a set of backgrounds on
a Cell and Communications Tower theme.
This theme uses the Squared-blue style from the [`xde-styles`][11]
package.

The source for `xde-theme-towers` is hosted on [GitHub][1].


Release
-------

This is the `xde-theme-towers-1.2` package, released 2021-12-08.
This release, and the latest version, can be obtained from [GitHub][1],
using a command such as:

    $> git clone https://github.com/bbidulock/xde-theme-towers.git

Please see the [RELEASE][3] and [NEWS][4] files for release notes and
history of user visible changes for the current version, and the
[ChangeLog][5] file for a more detailed history of implementation
changes.  The [TODO][6] file lists features not yet implemented and
other outstanding items.

Please see the [INSTALL][8] file for installation instructions.

When working from `git(1)`, please use this file.  An abbreviated
installation procedure that works for most applications appears below.

This release is published under CCPL:cc-by-nc-nd-3.0 (primarily because
the base styles used to develop these styles were licensed under this
license).
Please see the license in the file [COPYING][10].


Quick Start
-----------

The quickest and easiest way to get `xde-theme-towers` up and
running is to run the following commands:

    $> git clone https://github.com/bbidulock/xde-theme-towers.git
    $> cd xde-theme-towers
    $> ./autogen.sh
    $> ./configure
    $> make
    $> make DESTDIR="$pkgdir" install

This will configure, compile and install `xde-theme-towers` the
quickest.  For those who like to spend the extra 15 seconds reading
`./configure --help`, some compile time options can be turned on and off
before the build.

For general information on GNU's `./configure`, see the file
[INSTALL][8].


Prerequisites
-------------

This package needs the [`xde-styles`][11] package to be useful and also
requires the `xde-setbg(1)` program from the [`xde-ctools`][12] package.


Issues
------

Report issues on GitHub [here][2].


Samples
-------

Following is a sample screenshot of the theme taken under the [ADWM][13]
window manager:

![adwm.jpg](scrot/adwm.jpg "Wallpaper #6")

Following are the eight wallpapers included in the theme (consisting
primarily of shots I took of towers around Alberta using an old Canon
PowerShot):

![tower_bluesky4.jpg](images/tower_bluesky4.jpg "Wallpaper #1")
![tower_field1.jpg](images/tower_field1.jpg "Wallpaper #2")
![hoghorns_sillouette6.jpg](images/hoghorns_sillouette6.jpg "Wallpaper #3")
![tower_sky2.jpg](images/tower_sky2.jpg "Wallpaper #4")
![tower_backlit1.jpg](images/tower_backlit1.jpg "Wallpaper #5")
![tower_clouds1.jpg](images/tower_clouds1.jpg "Wallpaper #6")
![tower_sillouette3.jpg](images/tower_sillouette3.jpg "Wallpaper #7")
![tower_greysky3.jpg](images/tower_greysky3.jpg "Wallpaper #8")

Following are an additional thirty-two wallpapers that may be used to
customize the theme:

![array_rooftop1.jpg](images/array_rooftop1.jpg "Additional Image #1")
![hoghorns_sillouette1.jpg](images/hoghorns_sillouette1.jpg "Additional Image #2")
![hoghorns_sillouette2.jpg](images/hoghorns_sillouette2.jpg "Additional Image #3")
![hoghorns_sillouette3.jpg](images/hoghorns_sillouette3.jpg "Additional Image #4")
![hoghorns_sillouette4.jpg](images/hoghorns_sillouette4.jpg "Additional Image #5")
![hoghorns_sillouette5.jpg](images/hoghorns_sillouette5.jpg "Additional Image #6")
![hoghorns_sillouette7.jpg](images/hoghorns_sillouette7.jpg "Additional Image #7")
![tower_backlit2.jpg](images/tower_backlit2.jpg "Additional Image #8")
![tower_backlit3.jpg](images/tower_backlit3.jpg "Additional Image #9")
![tower_backlit4.jpg](images/tower_backlit4.jpg "Additional Image #10")
![tower_bluesky1.jpg](images/tower_bluesky1.jpg "Additional Image #11")
![tower_bluesky2.jpg](images/tower_bluesky2.jpg "Additional Image #12")
![tower_bluesky3.jpg](images/tower_bluesky3.jpg "Additional Image #13")
![tower_clouds2.jpg](images/tower_clouds2.jpg "Additional Image #14")
![tower_clouds3.jpg](images/tower_clouds3.jpg "Additional Image #15")
![tower_dusk.jpg](images/tower_dusk.jpg "Additional Image #16")
![tower_fence.jpg](images/tower_fence.jpg "Additional Image #17")
![tower_field2.jpg](images/tower_field2.jpg "Additional Image #18")
![tower_field3.jpg](images/tower_field3.jpg "Additional Image #19")
![tower_flatsky.jpg](images/tower_flatsky.jpg "Additional Image #20")
![tower_greysky1.jpg](images/tower_greysky1.jpg "Additional Image #21")
![tower_greysky2.jpg](images/tower_greysky2.jpg "Additional Image #22")
![tower_horns1.jpg](images/tower_horns1.jpg "Additional Image #23")
![tower_ring.jpg](images/tower_ring.jpg "Additional Image #24")
![tower_sillouette1.jpg](images/tower_sillouette1.jpg "Additional Image #25")
![tower_sillouette2.jpg](images/tower_sillouette2.jpg "Additional Image #26")
![tower_sillouette4.jpg](images/tower_sillouette4.jpg "Additional Image #27")
![tower_sky1.jpg](images/tower_sky1.jpg "Additional Image #28")
![tower_sky3.jpg](images/tower_sky3.jpg "Additional Image #29")
![tower_sky4.jpg](images/tower_sky4.jpg "Additional Image #30")
![tower_sky.jpg](images/tower_sky.jpg "Additional Image #31")
![tower_tree.jpg](images/tower_tree.jpg "Additional Image #32")



[1]: https://github.com/bbidulock/xde-theme-towers
[2]: https://github.com/bbidulock/xde-theme-towers/issues
[3]: https://github.com/bbidulock/xde-theme-towers/blob/1.2/RELEASE
[4]: https://github.com/bbidulock/xde-theme-towers/blob/1.2/NEWS
[5]: https://github.com/bbidulock/xde-theme-towers/blob/1.2/ChangeLog
[6]: https://github.com/bbidulock/xde-theme-towers/blob/1.2/TODO
[7]: https://github.com/bbidulock/xde-theme-towers/blob/1.2/COMPLIANCE
[8]: https://github.com/bbidulock/xde-theme-towers/blob/1.2/INSTALL
[9]: https://github.com/bbidulock/xde-theme-towers/blob/1.2/LICENSE
[10]: https://github.com/bbidulock/xde-theme-towers/blob/1.2/COPYING
[11]: https://github.com/bbidulock/xde-styles
[12]: https://github.com/bbidulock/xde-ctools
[13]: https://bbidulock.github.io/adwm

[ vim: set ft=markdown sw=4 tw=72 nocin nosi fo+=tcqlorn spell: ]: #
