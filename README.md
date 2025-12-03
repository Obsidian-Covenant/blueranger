# blueranger

## Modernization Covenant

This is a refactored and modernized edition of **blueranger**, a script which uses Link Quality to locate Bluetooth device radios.

The source code has been patched by using [Offensive Security patches](https://gitlab.com/kalilinux/packages/asleap) and further hardened to be compliant with strict toolchain rules.

Key changes:

- ✅ Small patch on the helper

### Installation

#### From source

```bash
git clone https://github.com/Obsidian-Covenant/blueranger.git
cd blueranger
sudo install -Dm 755 blueranger.sh /usr/bin/blueranger
```

### Usage

Use the Bluetooth interface (i.e., `hci1`) to scan for the specified remote address (`20:C9:D0:43:4B:D8`):
```
blueranger hci1 20:C9:D0:43:4B:D8
```
```
Starting ...

Close with 2 X Crtl+C


      (((B(l(u(e(R)a)n)g)e)r)))

By JP Dunning (.ronin)
www.hackfromacave.com

Locating: ares (20:C9:D0:43:4B:D8)
Ping Count: 1

Proximity Change    Link Quality
----------------    ------------
FOUND           255/255

Range
------------------------------------
|*
------------------------------------
```