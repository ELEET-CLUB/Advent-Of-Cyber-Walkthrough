# Advent-Of-Cyber-Walkthrough
Get started with Cyber Security in 24 Days - learn the basics by doing a new, beginner-friendly security challenge every day leading up to Christmas.




Download and install Cherry Tre from https://www.giuspen.net/cherrytree/ and open the file with it
  
download

Download last stable version 0.99.53 (December 11th, 2022 – changelog) :

tar.gz archive Source code (GPLv3+): cherrytree_0.99.53.tar.xz
with signature cherrytree_0.99.53.tar.xz.asc and key:
terminal gpg --keyserver keyserver.ubuntu.com --recv-keys C7BF38CE0BD442C2369AA984049128A20CE0648D
terminal gpg --verify PATH.tar.xz.asc
( NOTE: also available under github releases )

linuxubuntu package Ubuntu bionic 18.04 LTS / focal 20.04 LTS / jammy 22.04 LTS / kinetic 22.10
(giuspen PPA: sudo add-apt-repository ppa:giuspen/ppa)
https://launchpad.net/~giuspen/+archive/ubuntu/ppa/+packages

linuxdebian package Debian 11 cherrytree_0.99.53-2~Debian11_amd64.deb
Debian 10 cherrytree_0.99.53-2~Debian10_amd64.deb

linuxrpm package Fedora 31+ see https://copr.fedorainfracloud.org/coprs/bcotton/cherrytree/

linuxappimage package AppImage CherryTree-0.99.53-x86_64.AppImage (all in one file, after downloading make it executable and then run it from a terminal or just double click)

linuxflatpak package Flatpak https://flathub.org/apps/details/net.giuspen.cherrytree

linuxsnap package Snap https://snapcraft.io/cherrytree

mac os homebrew Mac OS X Installer (by @dehesselle) https://gitlab.com/dehesselle/cherrytree_macos/-/releases
or Homebrew https://formulae.brew.sh/formula/cherrytree
or Mac Ports https://ports.macports.org/port/cherrytree

7z archive Microsoft windows installer: cherrytree_0.99.53.0_win64_setup.exe [old pygtk2 cherrytree_0.39.4_setup.exe]

7z archive Microsoft windows portable archive: cherrytree_0.99.53.0_win64_portable.7z (look for mingw64/bin/cherrytree.exe; for portable config put config.cfg in portable folder root, beside license.txt) [old pygtk2 cherrytree_0.39.4_win32_portable.7z]

terminal
480e8fc29a02b66c74a47eb8f4865a8704687a40fbfbd302ff1cca203328f57f cherrytree_0.99.53.0_win64_portable.7z
07db1dcd649a342710bb7436c67d7252b502030aec1cd3ad8bb9c9dc11f8d349 cherrytree_0.99.53.0_win64_setup.exe
448816beea68f2ffa7a84585606c7a9bd18945f409b2597e7e2801848d518e33 cherrytree_0.99.53-2~Debian10_amd64.deb
a0029e44d6f705e887a6b84799b9ef1fe9085b93cdd46ecac10e6212f667ec2b cherrytree_0.99.53-2~Debian11_amd64.deb
317fbac7627b6556c7113433b360376d332bd10b6529b43734a8640cef5de24e cherrytree_0.99.53.tar.xz
0f118b94f4ffbd97dd9f4bed474a90978c9c4f2c44e7aa8c27ef0cfcfb4ad8ab cherrytree_0.99.53.tar.xz.asc
7a6676b33db8ebc1c58a7283e517f8a81f3c9cd4b9303664ae980f52395b3732 CherryTree-0.99.53-x86_64.AppImage  
