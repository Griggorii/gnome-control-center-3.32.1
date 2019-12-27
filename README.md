# gnome-control-center-3.32.1
gnome-control-center-3.32.1 source 

ninja -C .build install

Система-System.tar.gz root arhive run inpack /

sudo apt update && sudo apt --reinstall install libpulse-dev gir1.2-colord-1.0 libcolord-dev gsettings-desktop-schemas-dev libgnome-desktop-3-dev libseccomp-dev libudev-dev gnome-settings-daemon-dev libgoa-1.0-dev libgoa-backend-1.0-dev libupower-glib-dev libcups2-dev libcupsfilters-dev libcupsimage2-dev libgutenprint-dev libjbig-dev libjpeg-dev libjpeg-turbo8-dev libjpeg8-dev liblzma-dev libtiff-dev libtiffxx5 cups-filters autopoint debhelper dh-autoreconf dh-strip-nondeterminism dwz gir1.2-clutter-gst-3.0 libarchive-cpio-perl libcheese-dev libclutter-1.0-dev libclutter-gst-3.0-dev libcogl-dev libcogl-pango-dev libcogl-path-dev libevdev-dev libfile-stripnondeterminism-perl libgbm-dev libgles2-mesa-dev libgstreamer-plugins-base1.0-dev libgstreamer1.0-dev libinput-dev libjson-glib-dev libltdl-dev libmail-sendmail-perl libmtdev-dev liborc-0.4-dev liborc-0.4-dev-bin libsys-hostname-long-perl libtool libwacom-dev po-debconf libcanberra-dev libcanberra-gtk-common-dev libcanberra-gtk3-dev libcheese-gtk-dev libclutter-gtk-1.0-dev libibus-1.0-dev libgudev-1.0-dev gir1.2-networkmanager-1.0 libdbus-glib-1-dev libdbus-glib-1-dev-bin libnm-dev libnm-glib-dev libnm-glib-vpn-dev libnm-glib-vpn1 libnm-gtk-dev libnm-util-dev network-manager-dev libnma-dev libnmz7 libnmz7-dev gir1.2-modemmanager-1.0 libmm-glib-dev modemmanager-dev libbluetooth-dev libnotify-dev gir1.2-grilo-0.3 libgrilo-0.3-dev gir1.2-colordgtk-1.0 libcolord-gtk-dev libudisks2-dev libgtop2-dev libsmbclient-dev libsecret-1-dev gir1.2-gsound-1.0 libgsound-dev comerr-dev krb5-multidev libgssrpc4 libkadm5clnt-mit11 libkadm5srv-mit11 libkdb5-9 libkrb5-dev libpwquality-dev  libaccountsservice-dev libgnome-bluetooth-dev libbluetooth-dev libmm-glib-dev 

inpack gnome-control-center-3.32

cd gnome-control-center-3.32.1

ninja -C .build install

run gnome-control-center

sudo apt --reinstall install gnome-control-center

Фаилы Система-System могут быть уже не нужны в 2019 это уже решает пакет выше libgnome-bluetooth-dev
Если после этих вещей что либо случиться и что либо пропадёт то придётся удалить по структуре закинутые фаилы Система-System
 мои системы которые собраны https://github.com/Griggorii/Cinnamon-Budgie-Linux-OS-20-based-19.10-Ubuntu-Pop
