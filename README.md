# Create Debian .deb package for Rust Web Server
To build rws as Debian package, put prebuilt binary rws at rws-create-deb/usr/bin, update rws-create-deb/DEBIAN/control file, and execute:
> dpkg-deb --build rws-create-deb
> 
> mv rws-create-deb.deb rws.deb

To install package execute:
> sudo dpkg -i --force-overwrite rws.deb

To check installation:
> rws

Note: you may build almost any rust project as debian package
by updating control file and replacing rws with your executable.
As an example Rust TLS server is built using this template.

## Community
Use GitHub discussions, issues and pull requests.

There is Rust Web Server [Discord](https://discord.gg/zaErjtr5Dm) where you can ask questions and share ideas.

Follow the [Rust code of conduct](https://www.rust-lang.org/policies/code-of-conduct).

## Donations
If you appreciate my work and want to support it, feel free to do it via [PayPal](https://www.paypal.com/donate/?hosted_button_id=7J69SYZWSP6HJ).

## Links
1. [Rust Web Server](https://github.com/bohdaq/rust-web-server)
1. [Rust TLS Server](https://github.com/bohdaq/rust-tls-server)
1. [http-to-https-letsencrypt](https://github.com/bohdaq/rust-http-to-https-letsencrypt-acme)
1. [Rust Web Framework](https://github.com/bohdaq/rust-web-framework/)
1. [Create RPM Package](https://github.com/bohdaq/rws-rpm-builder)
1. [Homebrew Formula Rust TLS Server](https://github.com/bohdaq/homebrew-rust-tls-server)
1. [Homebrew Formula Rust Web Server](https://github.com/bohdaq/homebrew-rust-web-server)

