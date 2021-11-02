## Dolphin service menu: xxHash - extremely fast directory checksum / hash

Creates a file with checksums / hashes of all files in a directory (recursively) using extremely fast xxHash algorithm. You can create 64 bit and 128 bit (new XXH3) hashes.

Supported languages: Dutch, English, Russian  
Adding support for your language is very simple: just add `Name[xx]=…` for it in `.desktop` file and create a pull request :wink:

---

This project uses xxHash. Please, make sure `xxhash` package is installed. XXH3 became stable in version 0.8.0, so I recommend this version or newer.

xxHash 0.8+ is available in Ubuntu 20.10+, Debian 11+, Fedora 32+, Arch, openSUSE Tumbleweed, etc.

If your distro has old version, you can get newer one from Arch package (better check package signature before unpacking):

`wget -qO xxhash.tzst https://www.archlinux.org/packages/community/x86_64/xxhash/download/ && sudo tar -C / -xvf xxhash.tzst usr/bin`

See [SMhasher](https://rurban.github.io/smhasher) for comparison with other hash algorithms.

![Screenshot](screenshot.png)

![Screenshot](screenshot-2.png)
