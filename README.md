## Dolphin service menu: xxHash - extremely fast directory checksum / hash

Creates a file with checksums / hashes of all files in a directory using extremely fast xxHash algorithm.

**Supported languages:** Dutch, English, Russian  
<details><summary>Adding support for your language is very simple:</summary>

Just add `Name[xx]=…` translated entries for it in `.desktop` file and create a pull request :wink:  
To do so in GitHub web interface, you can edit file right there, then click `Propose changes` → `Create pull request`.
</details>

### Installation:
Place `.desktop` file in `~/.local/share/kio/servicemenus`

---

This project uses xxHash. Please, make sure <code>xxhash</code> package is installed.

See [SMhasher](https://rurban.github.io/smhasher) for comparison with other hash algorithms.

![Screenshot](screenshot.png)

![Screenshot](screenshot-2.png)
