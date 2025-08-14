[mkarchiso] INFO: Validating options...
[mkarchiso] INFO: Done!
[mkarchiso] INFO: mkarchiso configuration settings
[mkarchiso] INFO:              Architecture:   x86_64
[mkarchiso] INFO:         Working directory:   /home/soyo/krypton-i3/work
[mkarchiso] INFO:    Installation directory:   arch
[mkarchiso] INFO:                Build date:   2025-06-15T18:38+0900
[mkarchiso] INFO:          Output directory:   /home/soyo/krypton-i3/out
[mkarchiso] INFO:        Current build mode:   iso
[mkarchiso] INFO:               Build modes:   iso
[mkarchiso] INFO:                   GPG key:   None
[mkarchiso] INFO:                GPG signer:   None
[mkarchiso] INFO: Code signing certificates:   None
[mkarchiso] INFO:                   Profile:   /home/soyo/krypton-i3/configs
[mkarchiso] INFO: Pacman configuration file:   /home/soyo/krypton-i3/configs/pacman.conf
[mkarchiso] INFO:           Image file name:   krypton-2025.06.15-x86_64.iso
[mkarchiso] INFO:          ISO volume label:   ARCH_202506
[mkarchiso] INFO:             ISO publisher:   Itsuki0222 <https://itsuki0222.f5.si>
[mkarchiso] INFO:           ISO application:   Krypton Live/Install DVD
[mkarchiso] INFO:                Boot modes:   bios.syslinux.mbr bios.syslinux.eltorito uefi-ia32.grub.esp uefi-x64.grub.esp uefi-ia32.grub.eltorito uefi-x64.grub.eltorito
[mkarchiso] INFO:             Packages File:   /home/soyo/krypton-i3/configs/packages.x86_64
[mkarchiso] INFO:                  Packages:   alsa-utils alsa-firmware amd-ucode arch-install-scripts archinstall base bcachefs-tools bind bolt brltty btrfs-progs cloud-init cryptsetup darkhttpd ddrescue dhclient dhcpcd diffutils dmidecode dmraid dnsmasq dosfstools e2fsprogs edk2-shell efibootmgr espeakup ethtool exfatprogs fatresize foot-terminfo fsarchiver gpart gpm gptfdisk grml-zsh-config grub hdparm hyperv intel-ucode irssi iw iwd jfsutils kitty-terminfo ldns less lftp libfido2 libusb-compat linux linux-atm linux-headers linux-firmware linux-firmware-marvell livecd-sounds lsscsi lvm2 man-db man-pages mc mdadm memtest86+ memtest86+-efi mkinitcpio mkinitcpio-archiso mkinitcpio-nfs-utils modemmanager mtools nano nbd ndisc6 nfs-utils nilfs-utils nmap ntfs-3g nvme-cli open-iscsi open-vm-tools openconnect openpgp-card-tools openssh openvpn partclone parted partimage pcsclite ppp pptpclient pv qemu-guest-agent refind reflector rp-pppoe rsync rxvt-unicode-terminfo screen sdparm sequoia-sq sg3_utils smartmontools sof-firmware squashfs-tools sudo syslinux systemd-resolvconf tcpdump terminus-font testdisk tpm2-tools tpm2-tss udftools usb_modeswitch usbmuxd usbutils vim virtualbox-guest-utils-nox vpnc wireless-regdb wireless_tools wpa_supplicant wvdial xfsprogs xl2tpd zsh xorg xorg-server xapps sddm i3 okular alacritty thunar kate ark spectacle brave-bin gwenview power-profiles-daemon papirus-icon-theme flatpak fwupd feh pipewire pipewire-pulse pavucontrol noto-fonts-cjk fcitx5 fcitx5-im fcitx5-mozc kryptinfo calamares archiso-calamares-config git go yay ttf-hack-nerd powerline eza
[mkarchiso] INFO: Copying custom pacman.conf to work directory...
[mkarchiso] INFO: Using pacman CacheDir: /var/cache/pacman/pkg/
[mkarchiso] INFO: Copying custom airootfs files...
[mkarchiso] INFO: Done!
[mkarchiso] INFO: Installing packages to '/home/soyo/krypton-i3/work/x86_64/airootfs/'...
==> Creating install root at /home/soyo/krypton-i3/work/x86_64/airootfs
==> Installing packages to /home/soyo/krypton-i3/work/x86_64/airootfs
:: Synchronizing package databases...
 core                                                                                             116.2 KiB   352 KiB/s 00:00 [############################################################################] 100% extra                                                                                              7.8 MiB  3.21 MiB/s 00:02 [############################################################################] 100% krypton-core                                                                                    1116.0   B  5.45 KiB/s 00:00 [############################################################################] 100% archlinuxcn                                                                                     1378.1 KiB  2027 KiB/s 00:01 [############################################################################] 100%:: There are 48 members in group xorg:
:: Repository extra
   1) xf86-video-vesa  2) xorg-bdftopcf  3) xorg-docs  4) xorg-font-util  5) xorg-fonts-100dpi  6) xorg-fonts-75dpi  7) xorg-fonts-encodings  8) xorg-iceauth  9) xorg-mkfontscale  10) xorg-server
   11) xorg-server-common  12) xorg-server-devel  13) xorg-server-xephyr  14) xorg-server-xnest  15) xorg-server-xvfb  16) xorg-sessreg  17) xorg-setxkbmap  18) xorg-smproxy  19) xorg-x11perf  20) xorg-xauth
   21) xorg-xbacklight  22) xorg-xcmsdb  23) xorg-xcursorgen  24) xorg-xdpyinfo  25) xorg-xdriinfo  26) xorg-xev  27) xorg-xgamma  28) xorg-xhost  29) xorg-xinput  30) xorg-xkbcomp  31) xorg-xkbevd
   32) xorg-xkbutils  33) xorg-xkill  34) xorg-xlsatoms  35) xorg-xlsclients  36) xorg-xmodmap  37) xorg-xpr  38) xorg-xprop  39) xorg-xrandr  40) xorg-xrdb  41) xorg-xrefresh  42) xorg-xset
   43) xorg-xsetroot  44) xorg-xvinfo  45) xorg-xwayland  46) xorg-xwd  47) xorg-xwininfo  48) xorg-xwud

Enter a selection (default=all):
:: There are 4 members in group i3:
:: Repository extra
   1) i3-wm  2) i3blocks  3) i3lock  4) i3status

Enter a selection (default=all):
:: There are 4 members in group fcitx5-im:
:: Repository extra
   1) fcitx5  2) fcitx5-configtool  3) fcitx5-gtk  4) fcitx5-qt

Enter a selection (default=all):
resolving dependencies...
:: There are 4 providers available for libxtables.so=12-64:
:: Repository core
   1) iptables  2) iptables-nft
:: Repository archlinuxcn
   3) iptables-fullconenat  4) iptables-fullconenat-nft

Enter a number (default=1):
:: There are 14 providers available for ttf-font:
:: Repository extra
   1) gnu-free-fonts  2) noto-fonts  3) ttf-bitstream-vera  4) ttf-croscore  5) ttf-dejavu  6) ttf-droid  7) ttf-ibm-plex  8) ttf-input  9) ttf-input-nerd  10) ttf-liberation  11) ttf-roboto
:: Repository archlinuxcn
   12) ttf-noto-sans-mono-vf  13) ttf-noto-sans-vf  14) ttf-noto-serif-vf

Enter a number (default=1):
:: There are 2 providers available for qt6-multimedia-backend:
:: Repository extra
   1) qt6-multimedia-ffmpeg  2) qt6-multimedia-gstreamer

Enter a number (default=1):
:: There are 2 providers available for jack:
:: Repository extra
   1) jack2  2) pipewire-jack

Enter a number (default=1):
:: There are 3 providers available for phonon-qt6-backend:
:: Repository extra
   1) phonon-qt6-mpv  2) phonon-qt6-vlc
:: Repository archlinuxcn
   3) phonon-qt6-mpv-git

Enter a number (default=1):
looking for conflicting packages...
warning: dependency cycle detected:
warning: systemd-libs will be installed before its libcap dependency
warning: dependency cycle detected:
warning: harfbuzz will be installed before its freetype2 dependency
warning: dependency cycle detected:
warning: mesa will be installed before its libglvnd dependency
warning: dependency cycle detected:
warning: qt6-multimedia-ffmpeg will be installed before its qt6-multimedia dependency
warning: dependency cycle detected:
warning: phonon-qt6-mpv will be installed before its phonon-qt6 dependency

Packages (884) abseil-cpp-20250512.0-1  accounts-qml-module-0.7-6  acl-2.3.2-1  adwaita-cursors-48.1-1  adwaita-fonts-48.2-1  adwaita-icon-theme-48.1-1  adwaita-icon-theme-legacy-46.2-3
               alsa-card-profiles-1:1.4.5-1  alsa-lib-1.2.14-1  alsa-topology-conf-1.2.5.1-4  alsa-ucm-conf-1.2.14-2  aom-3.12.1-1  appstream-1.0.5-2  archlinux-keyring-20250430.1-1  at-spi2-core-2.56.2-1
               attica-6.14.0-1  attr-2.5.2-1  audit-4.0.5-1  avahi-1:0.8+r194+g3f79789-3  baloo-6.14.0-1  bash-5.2.037-5  binutils-2.44+r94+gfe459e33c676-1  blas-3.12.1-2  bluez-5.83-1  bluez-libs-5.83-1
               breeze-icons-6.14.0-1  brotli-1.1.0-3  bubblewrap-0.11.0-1  bzip2-1.0.8-6  ca-certificates-20240618-1  ca-certificates-mozilla-3.112-1  ca-certificates-utils-20240618-1  cairo-1.18.4-1
               cairomm-1.16-1.18.0-1  cblas-3.12.1-2  ccid-1.6.2-1  cdparanoia-10.2-9  cfitsio-1:4.6.2-1  ckbcomp-1.237-1  composefs-1.0.8-1  confuse-3.3-4  convertlit-1.8-12  coreutils-9.7-1
               cracklib-2.10.3-1  curl-8.14.1-1  dav1d-1.5.1-1  db5.3-5.3.28-5  dbus-1.16.2-1  dbus-broker-36-4  dbus-broker-units-36-4  dbus-units-36-4  dconf-0.40.0-3  default-cursors-3-1
               desktop-file-utils-0.28-1  device-mapper-2.03.32-1  ding-libs-0.6.2-2  discount-3.0.0.d-1  djvulibre-3.5.28-6  dnssec-anchors-20250524-1  double-conversion-3.3.1-1  duktape-2.7.0-7
               ebook-tools-0.2.2-9  editorconfig-core-c-0.12.9-1  efivar-39-1  ell-0.77-1  enchant-2.8.2-2  espeak-ng-1.52.0-1  exiv2-0.28.5-1  exo-4.20.0-2  expat-2.7.1-1  f2fs-tools-1.16.0-3
               fastfetch-2.45.0-1  ffmpeg-2:7.1.1-4  fftw-3.3.10-7  file-5.46-4  filesystem-2025.05.03-1  findutils-4.10.0-2  flac-1.5.0-1  flashrom-1.5.1-1  flex-2.6.4-5  fontconfig-2:2.16.2-1
               freeglut-3.6.0-2  freetype2-2.13.3-3  fribidi-1.0.16-2  fuse-common-3.17.1-1  fuse2-2.9.9-5  fuse3-3.17.1-1  fwupd-efi-1.7-1  gawk-5.3.2-1  gcc-libs-15.1.1+r7+gf36ec88aa85a-1  gdbm-1.25-1
               gdk-pixbuf2-2.42.12-2  gettext-0.25-1  ghostscript-10.05.1-2  giflib-5.2.2-2  glib-networking-1:2.80.1-1  glib2-2.84.2-1  glibc-2.41+r48+g5cb575ca9a3d-1  glibmm-2.68-2.84.0-1
               glslang-1:1.4.313.0-1  glu-9.0.3-2  gmp-6.3.0-2  gnu-free-fonts-20120503-8  gnulib-l10n-20241231-1  gnupg-2.4.7-3  gnutls-3.8.9-1  gobject-introspection-runtime-1.84.0-2  gperftools-2.16-1
               gpgme-2.0.0-1  gpgmepp-2.0.0-2  graphene-1.10.8-2  graphite-1:1.3.14-4  grep-3.12-2  groff-1.23.0-7  gsettings-desktop-schemas-48.0-1  gsettings-system-schemas-48.0-1  gsm-1.0.22-2
               gssdp-1.6.3-2  gssproxy-0.9.2-1  gst-plugins-bad-libs-1.26.2-2  gst-plugins-base-1.26.2-2  gst-plugins-base-libs-1.26.2-2  gstreamer-1.26.2-2  gtest-1.17.0-1  gtk-update-icon-cache-1:4.18.6-1
               gtk3-1:3.24.49-2  gtk4-1:4.18.6-1  gtkmm-4.0-4.18.0-2  gupnp-1:1.6.8-2  gupnp-igd-1.6.0-2  gzip-1.14-2  harfbuzz-11.2.1-1  hicolor-icon-theme-0.18-1  hidapi-0.15.0-1  highway-1.2.0-1
               hwdata-0.396-1  hwinfo-24.0-1  hwloc-2.12.1-1  iana-etc-20250502-1  icu-76.1-1  ijs-0.35-6  imath-3.1.12-4  imlib2-1.12.5-1  iproute2-6.15.0-1  iptables-1:1.8.11-2  iputils-20250605-1
               iso-codes-4.18.0-1  jack2-1.9.22-1  jansson-2.14.1-1  jasper-4.2.5-1  jbig2dec-0.20-1  jbigkit-2.1-8  jemalloc-1:5.3.0-5  json-c-0.18-2  json-glib-1.10.6-1  kaccounts-integration-25.04.2-1
               karchive-6.14.0-1  kauth-6.14.0-1  kbd-2.8.0-1  kbookmarks-6.14.0-1  kcmutils-6.14.0-1  kcodecs-6.14.0-1  kcolorpicker-0.3.1-4  kcolorscheme-6.14.0-1  kcompletion-6.14.0-1  kconfig-6.14.0-1
               kconfigwidgets-6.14.0-1  kcoreaddons-6.14.0-1  kcrash-6.14.0-1  kdbusaddons-6.14.0-1  keyutils-1.6.3-3  kfilemetadata-6.14.0-1  kglobalaccel-6.14.0-1  kguiaddons-6.14.0-1  ki18n-6.14.0-1
               kiconthemes-6.14.0-1  kidletime-6.14.0-1  kimageannotator-0.7.1-3  kio-6.14.0-1  kirigami-6.14.1-1  kitemmodels-6.14.0-1  kitemviews-6.14.0-1  kjobwidgets-6.14.0-1  kmod-34.2-1
               knewstuff-6.14.0-1  knotifications-6.14.0-1  kpackage-6.14.0-1  kparts-6.14.0-1  kpipewire-6.3.5-1  kpmcore-25.04.2-1  kpty-6.14.0-1  krb5-1.21.3-1  kservice-6.14.0-1
               kstatusnotifieritem-6.14.0-1  ktexteditor-6.14.0-1  ktextwidgets-6.14.0-1  kuserfeedback-6.14.0-1  kwallet-6.14.1-3  kwidgetsaddons-6.14.0-1  kwindowsystem-6.14.0-1  kxmlgui-6.14.0-1
               l-smash-2.14.5-4  lame-3.100-5  lapack-3.12.1-2  layer-shell-qt-6.3.5-2  lcms2-2.17-1  leancrypto-1.4.0-1  libaccounts-glib-1.27-3  libaccounts-qt-1.17-1  libaio-0.3.113-3  libarchive-3.8.1-1
               libass-0.17.3-1  libassuan-3.0.0-1  libasyncns-1:0.8+r3+g68cd5af-3  libatasmart-0.19-6  libavc1394-0.5.4-6  libb2-0.98.1-3  libblockdev-3.3.0-1  libblockdev-crypto-3.3.0-1
               libblockdev-fs-3.3.0-1  libblockdev-loop-3.3.0-1  libblockdev-mdraid-3.3.0-1  libblockdev-nvme-3.3.0-1  libblockdev-part-3.3.0-1  libblockdev-swap-3.3.0-1  libbluray-1.3.4-3  libbpf-1.5.1-1
               libbs2b-3.1.0-9  libbsd-0.12.2-2  libbytesize-2.11-1  libcanberra-1:0.30+r2+gc0620e4-4  libcap-2.76-1  libcap-ng-0.8.5-3  libcbor-0.11.0-1  libcdio-2.2.0-1  libcdio-paranoia-10.2+2.0.2-1
               libcloudproviders-0.3.6-2  libcolord-1.4.7-2  libcups-2:2.4.12-2  libdaemon-0.14-6  libdatrie-0.2.13-4  libdbusmenu-glib-16.04.0.r498-2  libdbusmenu-gtk3-16.04.0.r498-2  libdc1394-2.2.7-1
               libdecor-0.2.3-1  libdeflate-1.23-1  libdisplay-info-0.2.0-2  libdmtx-0.7.8-1  libdnet-1.18.0-1  libdovi-3.3.1-1  libdrm-2.4.125-1  libdvdnav-6.1.1-2  libdvdread-6.1.3-2  libebur128-1.2.6-2
               libedit-20250104_3.1-1  libei-1.4.1-1  libelf-0.193-2  libepoxy-1.5.10-3  libev-4.33-3  libevdev-1.13.4-1  libevent-2.1.12-4  libexif-0.6.25-1  libfdk-aac-2.0.3-1  libffi-3.5.0-1
               libfontenc-1.1.8-1  libfreeaptx-0.2.2-1  libftdi-1.5-7  libgcrypt-1.11.1-1  libgirepository-1.84.0-2  libgit2-1:1.9.1-1  libglvnd-1.7.0-3  libgnomekbd-1:3.28.1-1  libgpg-error-1.55-1
               libgtop-2.41.3-2  libgudev-238-3  libice-1.1.2-1  libidn-1.43-1  libidn2-2.3.7-1  libiec61883-1.2.0-8  libimobiledevice-1.3.0-16  libimobiledevice-glue-1.3.2-1  libinih-58-1  libinput-1.28.1-1
               libjcat-0.2.3-2  libjpeg-turbo-3.1.0-1  libjxl-0.11.1-3  libkdcraw-25.04.2-1  libkexiv2-25.04.2-1  libksba-1.6.7-2  liblc3-1.1.3-1  libldac-2.0.2.3-2  libldap-2.6.10-1  liblouis-3.34.0-1
               libmalcontent-0.13.0-1  libmaxminddb-1.12.2-2  libmbim-1.32.0-1  libmd-1.1.0-2  libmm-glib-1.24.0-1  libmng-2.0.3-4  libmnl-1.0.5-2  libmodplug-0.8.9.0-6  libmspack-1:1.11-1  libmysofa-1.3.3-1
               libnetfilter_conntrack-1.0.9-2  libnewt-0.52.25-1  libnfnetlink-1.0.2-2  libnftnl-1.2.9-1  libnghttp2-1.65.0-1  libnghttp3-1.10.1-1  libnice-0.1.22-2  libnl-3.11.0-1  libnotify-0.8.6-1
               libnsl-2.0.1-1  libnvme-1.13-1  libogg-1.3.5-2  libopenmpt-0.8.0-1  libotr-4.1.1-5  libp11-kit-0.25.5-1  libpaper-2.2.6-1  libpcap-1.10.5-3  libpciaccess-0.18.1-2  libpgm-5.3.128-3
               libpipeline-1.5.8-1  libpipewire-1:1.4.5-1  libplacebo-7.351.0-1  libplist-2.7.0-1  libpng-1.6.48-1  libproxy-0.5.9-1  libpsl-0.21.5-2  libpulse-17.0+r43+g3e2bb8a1e-1  libpwquality-1.4.5-6
               libqmi-1.36.0-1  libqrtr-glib-1.2.2-4  libraw-0.21.4-1  libraw1394-2.1.2-4  librsvg-2:2.60.0-2  libsamplerate-0.2.2-3  libsasl-2.1.28-5  libseccomp-2.5.6-1  libsecret-0.21.7-1
               libsigc++-2.12.1-1  libsigc++-3.0-3.6.0-1  libsixel-1.10.5-1  libsm-1.2.6-1  libsndfile-1.2.2-3  libsodium-1.0.20-1  libsonic-0.2.0-2  libsoup3-3.6.5-1  libsoxr-0.1.3-4  libspectre-0.2.12-2
               libspeechd-0.12.1-1  libssh-0.11.1-1  libssh2-1.11.1-1  libstemmer-3.0.1-1  libsysprof-capture-48.0-5  libtasn1-4.20.0-1  libthai-0.1.29-3  libtheora-1.2.0-1  libtiff-4.7.0-1  libtirpc-1.3.6-2
               libtommath-1.3.0-1  libtool-2.5.4+r23+g5b582aed-1  libunibreak-6.1-1  libunistring-1.3-1  libunwind-1.8.1-3  liburcu-0.15.1-1  liburing-2.9-1  libusb-1.0.29-1  libusbmuxd-2.1.1-1
               libutempter-1.2.3-1  libuv-1.51.0-1  libva-2.22.0-1  libvdpau-1.5-3  libverto-0.3.2-5  libvorbis-1.3.7-4  libvpl-2.15.0-1  libvpx-1.15.0-1  libwacom-2.15.0-2  libwebp-1.5.0-1
               libwireplumber-0.5.10-1  libx11-1.8.12-1  libx86emu-3.7-1  libxau-1.0.12-1  libxaw-1.0.16-1  libxcb-1.17.0-1  libxcomposite-0.4.6-2  libxcrypt-4.4.38-1  libxcursor-1.2.3-1  libxcvt-0.1.3-1
               libxdamage-1.1.6-2  libxdmcp-1.1.5-1  libxext-1.3.6-1  libxfce4ui-4.20.1-2  libxfce4util-4.20.1-1  libxfixes-6.0.1-2  libxfont2-2.0.7-1  libxft-2.3.9-1  libxi-1.8.2-1  libxinerama-1.1.5-2
               libxkbcommon-1.10.0-1  libxkbcommon-x11-1.10.0-1  libxkbfile-1.1.3-1  libxklavier-5.4-6  libxml2-2.14.3-1  libxmlb-0.3.22-1  libxmu-1.2.1-1  libxpm-3.5.17-2  libxpresent-1.0.1-2
               libxrandr-1.5.4-1  libxrender-0.9.12-1  libxshmfence-1.3.3-1  libxslt-1.1.43-2  libxss-1.2.4-2  libxt-1.3.1-1  libxtst-1.2.5-1  libxv-1.0.13-1  libxxf86vm-1.1.6-1  libyaml-0.2.5-3
               libzip-1.11.4-1  licenses-20240728-1  lilv-0.24.26-1  linux-api-headers-6.15-1  linux-firmware-whence-20250508.788aadc8-2  llhttp-9.2.1-2  llvm-libs-20.1.6-3  lm_sensors-1:3.6.2-1
               lmdb-0.9.33-1  lsb-release-2.0.r55.a25a4fc-1  lua-5.4.8-2  luajit-2.1.1748459687-1  lv2-1.18.10-1  lz4-1:1.10.0-2  lzo-2.10-5  m4-1.4.20-1  md4c-0.5.2-1  media-player-info-26-1  mesa-1:25.1.3-3
               minizip-1:1.3.1-2  mkinitcpio-busybox-1.36.1-1  mkinitcpio-openswap-0.1.0-6  mobile-broadband-provider-info-20240407-1  mpdecimal-4.0.1-1  mpfr-4.2.2-1  mpg123-1.33.0-1  mpv-1:0.40.0-3
               mtdev-1.1.7-1  mujs-1.3.6-1  ncurses-6.5-4  nettle-3.10.1-1  nfsidmap-2.8.3-2  nftables-1:1.1.3-1  npth-1.8-1  nspr-4.36-1  nss-3.112-1  numactl-2.0.19-1  oath-toolkit-2.6.12-2  ocl-icd-2.3.3-1
               onetbb-2022.1.0-1  open-isns-0.103-1  openal-1.24.3-1  openbsd-netcat-1.229_1-1  opencore-amr-0.1.6-2  opencv-4.11.0-13  openexr-3.3.4-1  openjpeg2-2.5.3-1  openssl-3.5.0-1  opus-1.5.2-1
               orc-0.4.41-1  ostree-2025.2-3  p11-kit-0.25.5-1  pacman-7.0.0.r6.gc685ae6-6  pacman-mirrorlist-20250522-1  pahole-1:1.30-2  pam-1.7.0-2  pambase-20230918-2  pango-1:1.56.3-1
               pangomm-2.48-2.56.1-1  passim-0.1.10-1  pcaudiolib-1.3-1  pciutils-3.13.0-2  pcre-8.45-4  pcre2-10.45-1  perl-5.40.2-1  perl-clone-0.47-1  perl-encode-locale-1.05-13  perl-error-0.17030-1
               perl-file-listing-6.16-4  perl-html-parser-3.83-1  perl-html-tagset-3.24-2  perl-http-cookiejar-0.014-3  perl-http-cookies-6.11-2  perl-http-daemon-6.16-4  perl-http-date-6.06-3
               perl-http-message-7.00-1  perl-http-negotiate-6.01-14  perl-io-html-1.004-6  perl-libwww-6.78-1  perl-lwp-mediatypes-6.04-6  perl-mailtools-2.22-1  perl-net-http-6.23-4  perl-timedate-2.33-7
               perl-try-tiny-0.32-2  perl-uri-5.31-1  perl-www-robotrules-6.02-14  perl-xml-parser-2.47-2  perl-xml-writer-0.900-4  phonon-qt6-4.12.0-4  phonon-qt6-mpv-0.1.0-3  pinentry-1.3.1-5
               pipewire-audio-1:1.4.5-1  pipewire-session-manager-1:1.4.5-1  pixman-0.46.2-1  pkcs11-helper-1.30.0-2  plasma-activities-6.3.5-1  polkit-126-2  polkit-qt6-0.200.0-1  poppler-25.06.0-1
               poppler-data-0.4.12-2  poppler-qt6-25.06.0-1  popt-1.19-2  portaudio-1:19.7.0-3  prison-6.14.0-1  procps-ng-4.0.5-3  protobuf-31.1-1  protobuf-c-1.5.2-4  psmisc-23.7-1  purpose-6.14.0-1
               python-3.13.3-1  python-annotated-types-0.7.0-2  python-attrs-25.3.0-1  python-cffi-1.17.1-2  python-charset-normalizer-3.4.2-1  python-configobj-5.0.9-5  python-cryptography-45.0.4-1
               python-gobject-3.52.3-3  python-idna-3.10-2  python-jinja-1:3.1.6-1  python-jsonpatch-1.33-4  python-jsonpointer-3.0.0-2  python-jsonschema-4.23.0-2
               python-jsonschema-specifications-2024.10.1-1  python-markupsafe-3.0.2-1  python-netifaces-0.11.0-7  python-oauthlib-3.2.2-4  python-pycparser-2.22-3  python-pydantic-2.11.6-1
               python-pydantic-core-2:2.33.2-2  python-pyparted-3.13.0-5  python-pyserial-3.5-7  python-referencing-0.35.1-3  python-requests-2.32.4-1  python-rpds-py-0.22.3-1
               python-typing-inspection-0.4.1-1  python-typing_extensions-4.13.2-1  python-urllib3-2.4.0-1  python-yaml-6.0.2-2  qca-qt6-2.3.10-2  qrencode-4.1.1-4  qt6-5compat-6.9.1-1  qt6-base-6.9.1-1
               qt6-declarative-6.9.1-1  qt6-imageformats-6.9.1-1  qt6-multimedia-6.9.1-1  qt6-multimedia-ffmpeg-6.9.1-1  qt6-positioning-6.9.1-1  qt6-shadertools-6.9.1-1  qt6-speech-6.9.1-1  qt6-svg-6.9.1-1
               qt6-translations-6.9.1-1  qt6-wayland-6.9.1-1  qt6-webchannel-6.9.1-1  qt6-webengine-6.9.1-1  rav1e-0.7.1-1  re2-1:20240702-5  readline-8.2.013-2  rpcbind-1.2.7-2  rtkit-0.13-3
               rubberband-4.0.0-1  run-parts-5.22-1  sbc-2.0-2  sdl2-compat-2.32.56-1  sdl3-3.2.16-1  sed-4.9-3  serd-0.32.4-1  shaderc-2025.2-2  shadow-4.17.4-1  shared-mime-info-2.4-2
               signon-kwallet-extension-25.04.2-1  signon-plugin-oauth2-0.25-3  signon-ui-0.17+20231016-3  signond-8.61-3  slang-2.3.3-3  snappy-1.2.2-2  solid-6.14.0-1  sonnet-6.14.0-1  sord-0.16.18-1
               sound-theme-freedesktop-0.8-6  speex-1.2.1-2  speexdsp-1.2.1-2  spirv-tools-1:1.4.313.0-1  sqlite-3.50.1-1  sratom-0.6.18-1  srt-1.5.4-1  startup-notification-0.12-8  stoken-0.92-5
               svt-av1-3.0.2-1  syndication-6.14.0-1  syntax-highlighting-6.14.0-1  sysfsutils-2.1.1-2  systemd-257.6-1  systemd-libs-257.6-1  systemd-sysvcompat-257.6-1  taglib-2.1-1  tar-1.35-2
               tcl-8.6.16-1  tdb-1.4.13-1  thin-provisioning-tools-1.1.0-1  threadweaver-6.14.0-1  tinysparql-3.9.2-2  tslib-1.23-1  tzdata-2025b-1  uchardet-0.0.8-3  udisks2-2.10.1-5  upower-1.90.9-1
               uriparser-0.9.8-1  util-linux-2.41-4  util-linux-libs-2.41-4  v4l-utils-1.30.1-1  vapoursynth-R70-2  verdict-1.4.2-1  vid.stab-1.1.1-2  vim-runtime-9.1.1431-1  vmaf-3.0.0-1
               volume_key-0.3.12-11  vulkan-icd-loader-1.4.313.0-1  wayland-1.23.1-2  webrtc-audio-processing-1-1.3-5  which-2.23-1  wireplumber-0.5.10-1  wvstreams-4.6.1-21  x264-3:0.164.r3108.31e19f9-2
               x265-4.1-1  xcb-imdkit-1.0.9-1  xcb-proto-1.17.0-3  xcb-util-0.4.1-2  xcb-util-cursor-0.1.5-1  xcb-util-image-0.4.1-3  xcb-util-keysyms-0.4.1-5  xcb-util-renderutil-0.3.10-2
               xcb-util-wm-0.4.2-2  xcb-util-xrm-1.3-3  xdg-dbus-proxy-0.1.6-1  xdg-desktop-portal-1.20.3-1  xdg-utils-1.2.1-1  xf86-input-libinput-1.5.0-1  xfconf-4.20.0-2  xkeyboard-config-2.45-1
               xmlsec-1.3.7-2  xorg-fonts-alias-100dpi-1.0.5-1  xorg-fonts-alias-75dpi-1.0.5-1  xorg-util-macros-1.20.2-1  xorgproto-2024.1-2  xvidcore-1.3.7-3  xxhash-0.8.3-1  xz-5.8.1-1  yajl-2.1.0-6
               yaml-cpp-0.8.0-2  yyjson-0.11.1-1  zeromq-4.3.5-2  zimg-3.0.5-1  zix-0.6.2-1  zlib-1:1.3.1-2  zlib-ng-2.2.4-1  zstd-1.5.7-2  zxing-cpp-2.3.0-5  alacritty-0.15.1-1  alsa-firmware-1.2.4-4
               alsa-utils-1.2.14-1  amd-ucode-20250508.788aadc8-2  arch-install-scripts-29-1  archinstall-3.0.8-1  archiso-calamares-config-73-1  ark-25.04.2-1  base-3-2  bcachefs-tools-3:1.25.2-1
               bind-9.20.9-1  bolt-0.9.9-1  brave-bin-1:1.79.123-1  brltty-6.7-5  btrfs-progs-6.14-1  calamares-3.3.14-2  cloud-init-25.1.2-1  cryptsetup-2.7.5-2  darkhttpd-1.16-2  ddrescue-1.29.1-1
               dhclient-4.4.3.P1-4  dhcpcd-10.2.4-1  diffutils-3.12-2  dmidecode-3.6-1  dmraid-1.0.0.rc16.3-15  dnsmasq-2.91-1  dosfstools-4.2-5  e2fsprogs-1.47.2-2  edk2-shell-202411-1  efibootmgr-18-3
               espeakup-0.90-3  ethtool-1:6.11-1  exfatprogs-1.2.9-1  eza-0.21.4-1  fatresize-1.1.0-2  fcitx5-5.1.12-1  fcitx5-configtool-5.1.9-1  fcitx5-gtk-5.1.3-1  fcitx5-mozc-2.31.5810.102.gb091429-1
               fcitx5-qt-5.1.9-6  feh-3.10.3-1  flatpak-1:1.16.1-1  foot-terminfo-1.22.3-1  fsarchiver-0.8.8-1  fwupd-2.0.11-1  git-2.49.0-2  go-2:1.24.4-1  gpart-0.3-5  gpm-1.20.7.r38.ge82d1a6-6
               gptfdisk-1.0.10-1  grml-zsh-config-0.19.19-1  grub-2:2.12.r292.g73d1c959-1  gwenview-25.04.2-1  hdparm-9.65-2  hyperv-6.15-1  i3-wm-4.24-1  i3blocks-1.5-4  i3lock-2.15-2  i3status-2.15-1
               intel-ucode-20250512-1  irssi-1.4.5-4  iw-6.9-1  iwd-3.8-1  jfsutils-1.1.15-9  kate-25.04.2-1  kitty-terminfo-0.42.1-1  kryptinfo-20250217-1  ldns-1.8.4-1  less-1:668-1  lftp-4.9.3-1
               libfido2-1.16.0-1  libusb-compat-0.1.8-2  linux-6.15.2.arch1-1  linux-atm-2.5.2-9  linux-firmware-20250508.788aadc8-2  linux-firmware-marvell-20250508.788aadc8-2  linux-headers-6.15.2.arch1-1
               livecd-sounds-1.0-3  lsscsi-0.32-2  lvm2-2.03.32-1  man-db-2.13.1-1  man-pages-6.14-1  mc-4.8.33-1  mdadm-4.4-1  memtest86+-7.20-2  memtest86+-efi-7.20-2  mkinitcpio-39.2-3
               mkinitcpio-archiso-72-1  mkinitcpio-nfs-utils-0.3-8  modemmanager-1.24.0-1  mtools-1:4.0.48-1  nano-8.4-1  nbd-3.26.1-2  ndisc6-1.0.8-1  nfs-utils-2.8.3-2  nilfs-utils-2.2.11-1  nmap-7.95-1
               noto-fonts-cjk-20240730-1  ntfs-3g-2022.10.3-2  nvme-cli-2.13-1  okular-25.04.2-1  open-iscsi-2.1.11-1  open-vm-tools-6:12.5.2-2  openconnect-1:9.12-4  openpgp-card-tools-0.11.9-1
               openssh-10.0p1-3  openvpn-2.6.14-1  papirus-icon-theme-20250501-1  partclone-0.3.37-1  parted-3.6-2  partimage-0.6.9-15  pavucontrol-1:6.1-1  pcsclite-2.3.3-1  pipewire-1:1.4.5-1
               pipewire-pulse-1:1.4.5-1  power-profiles-daemon-0.30-1  powerline-2.8.4-3  ppp-2.5.2-1  pptpclient-1.10.0-3  pv-1.9.31-1  qemu-guest-agent-10.0.0-6  refind-0.14.2-1  reflector-2023-3
               rp-pppoe-4.0-5  rsync-3.4.1-2  rxvt-unicode-terminfo-9.31-7  screen-5.0.1-3  sddm-0.21.0-6  sdparm-1.12-1  sequoia-sq-1.3.1-1  sg3_utils-1.48-1  smartmontools-7.5-1  sof-firmware-2025.05-1
               spectacle-1:6.3.5-1  squashfs-tools-4.7-1  sudo-1.9.16.p2-2  syslinux-6.04.pre3.r3.g05ac953c-3  systemd-resolvconf-257.6-1  tcpdump-4.99.5-1  terminus-font-4.49.1-7  testdisk-7.2-2
               thunar-4.20.3-1  tpm2-tools-5.7-1  tpm2-tss-4.1.3-1  ttf-hack-nerd-3.4.0-1  udftools-2.3-2  usb_modeswitch-2.6.2-1  usbmuxd-1.1.1-4  usbutils-018-1  vim-9.1.1431-1
               virtualbox-guest-utils-nox-7.1.10-1  vpnc-1:0.5.3.r539.r239-1  wireless-regdb-2025.02.20-1  wireless_tools-30.pre9-4  wpa_supplicant-2:2.11-3  wvdial-1.61-9  xapp-2.8.9-1
               xf86-video-vesa-2.6.0-2  xfsprogs-6.14.0-1  xl2tpd-1.3.19-1  xorg-bdftopcf-1.1.2-1  xorg-docs-1.7.3-2  xorg-font-util-1.4.1-2  xorg-fonts-100dpi-1.0.4-3  xorg-fonts-75dpi-1.0.4-2
               xorg-fonts-encodings-1.1.0-1  xorg-iceauth-1.0.10-1  xorg-mkfontscale-1.2.3-1  xorg-server-21.1.16-1  xorg-server-common-21.1.16-1  xorg-server-devel-21.1.16-1  xorg-server-xephyr-21.1.16-1
               xorg-server-xnest-21.1.16-1  xorg-server-xvfb-21.1.16-1  xorg-sessreg-1.1.4-1  xorg-setxkbmap-1.3.4-2  xorg-smproxy-1.0.8-1  xorg-x11perf-1.7.0-1  xorg-xauth-1.1.4-1  xorg-xbacklight-1.2.4-1
               xorg-xcmsdb-1.0.7-1  xorg-xcursorgen-1.0.9-1  xorg-xdpyinfo-1.3.4-2  xorg-xdriinfo-1.0.7-2  xorg-xev-1.2.6-1  xorg-xgamma-1.0.7-2  xorg-xhost-1.0.10-1  xorg-xinput-1.6.4-2  xorg-xkbcomp-1.4.7-1
               xorg-xkbevd-1.1.6-1  xorg-xkbutils-1.0.6-1  xorg-xkill-1.0.6-2  xorg-xlsatoms-1.1.4-2  xorg-xlsclients-1.1.5-2  xorg-xmodmap-1.0.11-2  xorg-xpr-1.2.0-1  xorg-xprop-1.2.8-1  xorg-xrandr-1.5.3-1
               xorg-xrdb-1.2.2-2  xorg-xrefresh-1.1.0-1  xorg-xset-1.2.5-2  xorg-xsetroot-1.1.3-2  xorg-xvinfo-1.1.5-2  xorg-xwayland-24.1.6-1  xorg-xwd-1.0.9-2  xorg-xwininfo-1.1.6-2  xorg-xwud-1.0.7-1
               yay-12.5.0-1  zsh-5.9-5

Total Installed Size:  5210.28 MiB

:: Proceed with installation? [Y/n]
(884/884) checking keys in keyring                                                                                            [############################################################################] 100%
(884/884) checking package integrity                                                                                          [############################################################################] 100%
(884/884) loading package files                                                                                               [############################################################################] 100%
(884/884) checking for file conflicts                                                                                         [############################################################################] 100%
error: failed to commit transaction (conflicting files)
i3-wm: /home/soyo/krypton-i3/work/x86_64/airootfs/usr/share/xsessions/i3.desktop exists in filesystem
Errors occurred, no packages were upgraded.
==> ERROR: Failed to install packages to new root
