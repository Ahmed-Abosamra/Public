cd ~
git clone https://github.com/yshui/picom.git
cd picom
meson --buildtype=release . build
ninja -C build
sudo ninja -C build install
