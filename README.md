# Create Debian .deb package for Rust Web Server
To build rws as Debian package, put prebuilt binary rws at rws-create-deb/usr/local/bin, update rws-create-deb/DEBIAN/control file, and execute:
> dpkg-deb --build rws-create-deb
> 
> mv rws-create-deb.deb rws.deb

To install package execute:
> sudo dpkg -i --force-overwrite rws.deb
