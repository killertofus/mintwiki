
<h1 align="center"> Visual Studio Code </h1>
----
Category: Software
---


from the [wiki](https://code.visualstudio.com) Visual Studio Code is a cross-platform text editor developed by Microsoft, built on the Electron framework.
---
<ol>
<li>  Installation

<a href="#section-1"> i. [proprietary](#proprietary) </a><br />
<a href="#section-1"> i.ii [flatpak](#flatpak) </a><br />
<a href="#section-1"> i.iii [manual](#manual) </a> <br />
<a href="#section-1"> ii. [opensource](#opensource) </a><br />
<a href="#section-1"> ii.i [warning](#warning) </a><br />
<a href="#section-1"> ii.iii [manual opensource](#manual_opensource) </a> <br />
<a href="#section-1"> ii.iii [manual opensource](#manual_opensource) </a> <br />
</li>



---

<ol>

##  proprietary
you can install it using 3 methods

1. from the website

2. flatpak

3. from the website
 

---
 to install it from flatpak 
run this command
## flatpak
```flatpak install flathub com.visualstudio.code```

## manual
install visualstudio from apt

`curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg
sudo install -o root -g root -m 644 microsoft.gpg /usr/share/keyrings/microsoft-archive-keyring.gpg
sudo sh -c 'echo "deb [arch=amd64,arm64,armhf signed-by=/usr/share/keyrings/microsoft-archive-keyring.gpg] https://packages.microsoft.com/repos/vscode stable main" > /etc/apt/sources.list.d/vscode.list`

Then update the package cache and install the package using:

`sudo apt-get update
sudo apt-get install code # or code-insiders`


---
## opensource
this is the Community open-source release.

## warning

One of Code's main strengths is its flexible API and rich extension ecosystem hosted on the [Microsoft Visual Studio Code Marketplace](https://marketplace.visualstudio.com/vscode). However, the [terms of use](https://aka.ms/vsmarketplace-ToU) only permit it to be used with the Microsoft branded releases. As a result, the Codium does not include a configured marketplace. The open-source release adds the Open VSIX extension registry, but this does not offer the same breadth of extensions. It is possible to bypass this limitation.


Known workarounds are:
* manually install the extension from its `.vsix` file, which can be obtained from the [Microsoft Visual Studio Code Marketplace](https://marketplace.visualstudio.com/);
* ask the maintainer to upload its extension to the [Open VSX registry](https://open-vsx.org/)
* add the Microsoft Visual Studio Code Marketplace by editing the `product.json`  Thas shown in [this github comment](https://github.com/VSCodium/vscodium/issues/418#issuecomment-643664182) after every package update.

It is useful to enable a [keyboard shortcut](https://stackoverflow.com/a/69985500) to reload the IDE when experimenting with changing `product.json`

flatpak
---
`flatpak install flathub com.vscodium.codium`

manual
---
`wget -qO - https://gitlab.com/paulcarroty/vscodium-deb-rpm-repo/raw/master/pub.gpg \
    | gpg --dearmor \
    | sudo dd of=/usr/share/keyrings/vscodium-archive-keyring.gpg`

</br>

Add the repository:
`echo 'deb [ signed-by=/usr/share/keyrings/vscodium-archive-keyring.gpg ] https://download.vscodium.com/debs vscodium main' \
    | sudo tee /etc/apt/sources.list.d/vscodium.list`
</br>
</br>
Update then install vscodium

`sudo apt update && sudo apt install codium`
