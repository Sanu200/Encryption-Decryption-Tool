<a href="https://github.com/THEncrypterX/THEncrypterX/actions/workflows/build-windows.yml"><img src="https://github.com/THEncrypterX/THEncrypterX/actions/workflows/build-windows.yml/badge.svg"></a>
<a href="https://github.com/THEncrypterX/THEncrypterX/actions/workflows/build-macos.yml"><img src="https://github.com/THEncrypterX/THEncrypterX/actions/workflows/build-macos.yml/badge.svg"></a>
<a href="https://github.com/THEncrypterX/THEncrypterX/actions/workflows/build-linux.yml"><img src="https://github.com/THEncrypterX/THEncrypterX/actions/workflows/build-linux.yml/badge.svg"></a>
<a href="https://github.com/THEncrypterX/THEncrypterX/actions/workflows/codeql-analysis.yml"><img src="https://github.com/THEncrypterX/THEncrypterX/actions/workflows/codeql-analysis.yml/badge.svg"></a>

<p align="center"><img align="center" src="/images/logo.svg" width="512" alt="THEncrypterX"></p> 

THEncrypterX is a very small, very simple, yet very secure encryption tool that you can use to protect your files. It's designed to be the go-to tool for encryption, with a focus on security, simplicity, and reliability. THEncrypterX uses the secure XChaCha20 cipher and the Argon2id key derivation function to provide a high level of security, even from three-letter agencies like the NSA. **Your privacy and security are under attack. Take it back with confidence by protecting your files with THEncrypterX.**

<p align="center"><img align="center" src="/images/screenshot.png" width="318" alt="THEncrypterX"></p>

# Downloads
**Make sure to only download THEncrypterX from this repository** to ensure that you get the authentic and backdoor-free THEncrypterX. When sharing THEncrypterX with others, be sure to link to this repository to prevent any confusion.

**Beware of thencrypterx.org, which claims to be the official website for this project! Remember, there is no official website for THEncrypterX.** Even if this self-proclaimed website is taken down, I will not remove this message; let it be a real-world warning to stay vigilant.

## Windows
THEncrypterX for Windows is as simple as it gets. To download the latest, standalone, and portable executable for Windows, click [here](https://github.com/THEncrypterX/THEncrypterX/releases/latest/download/THEncrypterX.exe). If Microsoft Defender or your antivirus flags THEncrypterX as a virus, please do your part and submit it as a false positive for the betterment of everyone.

If you use THEncrypterX frequently, you can download an installer [here](https://github.com/THEncrypterX/THEncrypterX/releases/download/1.47/Install-THEncrypterX.exe) for easier launching. It does not require any admin permissions to install and it also bundles a software OpenGL renderer for compatibility, so if the portable executable isn't working, this installer likely will.

## macOS
Download THEncrypterX [here](https://github.com/THEncrypterX/THEncrypterX/releases/latest/download/THEncrypterX.dmg), open the container, and drag THEncrypterX to your Applications. You may need to manually trust the app from a terminal and control-click on the app if macOS prevents you from opening it:
```
xattr -d com.apple.quarantine /Applications/THEncrypterX.app
```

## Linux
To use THEncrypterX on Linux, download the raw binary [here](https://github.com/THEncrypterX/THEncrypterX/releases/latest/download/THEncrypterX). Alternatively, you can try the [.deb](https://github.com/THEncrypterX/THEncrypterX/releases/latest/download/THEncrypterX.deb), [Flatpak](https://flathub.org/apps/io.github.thencrypterx.THEncrypterX), run THEncrypterX through Wine, or compile from source using the instructions in the `src/` directory.
```
sudo apt install -y libc6 libgcc-s1 libgl1 libgtk-3-0 libstdc++6 libx11-6
```

## Why THEncrypterX?
THEncrypterX is open-source, lightweight, and more secure than traditional encryption tools. Unlike BitLocker and most cloud services, THEncrypterX and its dependencies are fully auditable. It is built for security, simplicity, and reliability, making encryption accessible to all users.

## Features
- **XChaCha20 & Argon2id** for top-tier security
- **Metadata encryption** to prevent information leaks
- **Plausible deniability mode** for enhanced privacy
- **Portable & cross-platform compatibility**
- **Reed-Solomon error correction** to prevent data corruption
- **Fast, efficient encryption with real-time progress tracking**

## Security
For more information on the cryptographic methods used in THEncrypterX, refer to the [Internals](Internals.md) document. THEncrypterX operates under the assumption that the host machine is secure. If your device is compromised, no software can guarantee security.

## Acknowledgments
Special thanks to all contributors and security researchers who have helped test and improve THEncrypterX. This project is built to ensure that users maintain **full control over their data privacy and security.**