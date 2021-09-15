# How to Use
1. `pip install -r requirements.txt`
2. install the following dependencies

## [Arch](https://aur.archlinux.org/packages/ffmpeg-full/)
* `pacman -Su ffmpeg-full`

## [Debian](https://tracker.debian.org/pkg/ffmpeg)
* `sudo apt install ffmpeg`

## [Fedora](https://admin.rpmfusion.org/pkgdb/package/free/ffmpeg/) or similar
* `sudo dnf -y install https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm`
* `sudo dnf -y install https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm`
* `sudo dnf -y install ffmpeg ffmpeg-devel`

## [macOS](https://formulae.brew.sh/formula/ffmpeg)
* `brew install ffmpeg` (if you have [homebrew](https://docs.brew.sh/Installation) installed)

## [Ubuntu](https://launchpad.net/ubuntu/+source/ffmpeg)
* `sudo apt install ffmpeg`

## Windows
* [MS C++ Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/) (Desktop development with C++, including the optional features, MSVC v142, Windows 10 SDK, C++ CMake tools for Windows, Testing tools core features - Build Tools and C++ AddressSanitizer)
* [ffmpeg 4.4](https://github.com/GyanD/codexffmpeg/releases/tag/4.4) (if you have [chocolatey](https://chocolatey.org/install) installed, then `choco install ffmpeg`)
