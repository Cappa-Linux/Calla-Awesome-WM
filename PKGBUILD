pkgname="calla"
pkgver="0.4"
pkgrel="2"
pkgdesc="Calla desktop environement"
arch=("x86_64")
depends=("xorg-server" "pipewire-pulse"
  "brightnessctl" "inotify-tools"
  "awesome-git" "picom" "maim"
  "papirus-icon-theme" "noto-fonts"
  "noto-fonts-cjk" "noto-fonts-emoji"
  "noto-fonts-extra" "lua-pam-git")
url="https://github.com/Cappa-Linux/Calla-Awesome-WM"
optdepends=("st: terminal",
  "vim-gtk3: vim with clipboard",
  "nemo: file manager",
  "network-manager-gnome: network applet",
  "polkit-gnome: polkit",
  "cbatticon: battery applet",
  "blueman: bluetooth applet",
  "xdg-user-dirs: generate home directories",
  "lollypop: music player",)
package() {
  mkdir -p "${pkgdir}/usr/"
  cp -r "${srcdir}/usr/bin" "${pkgdir}/usr/"
  cp -r "${srcdir}/usr/share" "${pkgdir}/usr/"
}

