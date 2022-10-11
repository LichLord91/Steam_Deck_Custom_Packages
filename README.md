# Steam_Deck_Custom_Packages
Collection of useful programs that don't have a Steam Deck build or needed to modify them.

I will try to build with latest current stable, may add a beta builds later 


**Currently built with:** SteamOS 3.3.2


**General Install of all packages:**

```
sudo steamos-readonly disable

cd "to directory where the package exists"

sudo pacman -U (PackageName.zst)
```
**example:** `sudo pacman -U steam-metadata-editor-git-1.0.0.r36.bd0e2b3-1-any.pkg.tar.zst`

To uninstall
```
$ sudo pacman -R (PackageName.zst)
```

**Current Packages:**

- **Name:** Steam-Meta-Editor

  - **Source Url:** https://github.com/tralph3/Steam-Metadata-Editor

  - **Filename:** ***steam-metadata-editor-git-1.0.0.r36.bd0e2b3-1-any.pkg.tar.zst***

  - Compiled using this AUR pkg repo https://aur.archlinux.org/packages/steam-metadata-editor-git 
     - Commit: https://aur.archlinux.org/cgit/aur.git/commit/?h=steam-metadata-editor-git&id=7572a56dc28279b06d1b37a40c6fb371286b2fb
  - Launch from Konsole with `steammetadataeditor` or use the included 
  **Steam-Metadata-Editior.desktop** file I've added.

