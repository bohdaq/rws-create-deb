# Create Debian .deb package for Rust Web Server
To build rws, put rws at rws-create-deb/usr/local/bin, update DEBIAN/control file, and execute:
> dpkg-deb --build rws-create-deb
> mv rws-create-deb.deb rws.deb

To install package execute:
> sudo dpkg -i --force-overwrite rws.deb
