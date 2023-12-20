# BoxBuddy
An unofficial GUI for managing your Distroboxes. Written with GTK4 + Libadwaita.

Note that this does not come with Podman or Distrobox, those will need to be installed on the host.

![Main Menu](docs/screenshot-1.png)

## Installing

### Flatpak
<a href='https://flathub.org/apps/io.github.dvlv.boxbuddyrs'>
  <img width='240' alt='Download on Flathub' src='https://dl.flathub.org/assets/badges/flathub-badge-en.png'/>
</a>


### Local Binary
- Visit the [releases section](https://github.com/Dvlv/BoxBuddyRS/releases)
- Download and unzip the release
- Execute `./install.sh`


## Developing

Boxbuddy is written with Rust using Gtk4 and Libadwaita.

### Building Flatpak
- Install `flatpak-builder`
- `./singlefile.sh`
- `flatpak install --user boxbuddy.flatpak`

### Running Locally
- Install gtk4 development packages - check your distro for something like `gtk4-devel` or `gtk-dev`, etc.
- Install `rustup`
- Use the standard `cargo run` / `cargo build` workflow



