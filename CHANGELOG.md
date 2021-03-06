### CHANGELOG

#### Version 0.4.2

* fix a serious crash for some systems when the user was clicking the menu items Plasma or Latte was crashing
* various improvements for Unity style behavior
* fix behavior with Latte git version dragging/maximizing/restoring active window from panel empty areas
* dont register the global menu service under wayland in order for windows to keep their global menus in their windows
* fix warnings on startup


#### Version 0.4.1

* fix not showing menu items for all applications
* fix RTL menu items alignment

#### Version 0.4

* provide a Unity behavior option when used with Window Title v0.4 in latest Latte master
* support horizontal scrolling
* improve screen filtering

#### Version 0.3

* add an option in order to set spacing between menu items
* dont crash under wayland
* in edit mode show a menu sample in order to not show an empty space
* option to always fill maximum available space
* avoid empty QMenu (upstream plasma fix)
* reduce menu items spacing
* support new Latte Communicator mechanism

#### Version 0.2

* Scroll menu support when the menu is too big
* Option to show menus only from active/main windows
* support Latte painting for single button presentation
* dont hide menu when Latte is in editing mode (needs Latte>=0.9)
* show shortcuts properly when Alt is pressed

#### Version 0.1

* Minimize-state aware
* Multi-Screen aware
* Support Latte new painting
* based totally on official plasma appmenu applet in order to improve maintainability and code exchange
