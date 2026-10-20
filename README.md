# Bazzite Installation Guide
### A step-by-step guide by DeshaunDoesTech

Install Bazzite using its graphical installer. This repository contains documentation only: no scripts, terminal commands, or executable code.

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Support%20DeshaunDoesTech-FFDD00?logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/DeshaunDoesTech)

## Before you begin
Back up important files and verify the backup opens correctly. Keep your backup separate from the installation drive. An erase-disk installation destroys the selected drive's existing contents.

If keeping Windows, save your BitLocker recovery key somewhere accessible from another device before changing boot or disk settings.

## Step-by-step installation
1. Check your hardware using the compatibility information linked from the [official installation guide](https://docs.bazzite.gg/General/Installation_Guide/install-guide/).
2. Prepare a USB drive of at least 16 GB, a keyboard, and a mouse or touchscreen.
3. Visit [Bazzite's website](https://bazzite.gg/). Select your device, GPU vendor, desktop, and Gaming Mode preference; download the matching image.
4. Open Fedora Media Writer, select the downloaded image and your USB, and write it. Writing erases that USB.
5. Restart into your manufacturer's boot menu and select the USB.
6. Open the installer from the live desktop.
7. Choose language, region, and keyboard layout.
8. Select the destination disk carefully. If keeping Windows, follow the separate dual-boot instructions linked below instead of erasing its drive.
9. Decide whether to enable encryption. Keep its password safe and have a physical keyboard available for unlocking.
10. Create your user account.
11. Read the installation summary. Confirm the correct destination and proposed disk changes before starting.
12. Wait for completion, restart, and remove the installation USB.

## Secure Boot
For Secure Boot, Bazzite requires Universal Blue's signing key. On the blue enrollment screen, select **Enroll MOK**, follow the prompts, and enter **universalblue** when asked for the enrollment password. The prompt uses English QWERTY and may hide typed characters.

Choose **Continue boot** if Secure Boot is disabled or unsupported. Do not enable Secure Boot on a Steam Deck simply to follow this guide.

If you missed enrollment or encounter a signature error, use the [official Secure Boot guide](https://docs.bazzite.gg/General/Installation_Guide/secure_boot/). Its recovery procedure may require terminal commands; those commands are intentionally not reproduced here.

## Keeping Windows
Read the [official Windows dual-boot walkthrough](https://docs.bazzite.gg/General/Installation_Guide/install-guide/#dual-booting-windows) before changing partitions. Do not apply the erase-disk installation path to a disk containing Windows or files you want to retain.

Pause if you cannot identify a disk. Record its model and capacity, compare them with your existing system's storage information, and resolve any uncertainty before accepting changes.

## After installation
Use the [official Bazzite documentation](https://docs.bazzite.gg/) for post-installation setup and updates. Check your network, sound, display, and input devices before restoring all your files.

Keep a short record of the image you selected, installation date, and any problems. When seeking help, describe the device and the exact stage that failed. Never share account passwords, encryption passwords, or recovery keys.

## Quick troubleshooting
| Situation | Next step |
| --- | --- |
| Unsure which drive to select | Stop and identify the disk before continuing. |
| Installer looks different | Compare your screen with the current official guide. |
| USB does not appear in the boot menu | Check your manufacturer's USB boot instructions and whether the image was written successfully. |
| Secure Boot signature error | Follow the official Secure Boot recovery guide linked above. |
| An installation step fails | Record the error and consult the troubleshooting section of the official documentation. |

## Support my work
If this guide helped, [buy me a coffee](https://buymeacoffee.com/DeshaunDoesTech) to support more approachable tech guides.

## Sources and project scope
Installation and Secure Boot guidance checked against official Bazzite documentation on October 20, 2026:

- [Bazzite downloads](https://bazzite.gg/)
- [Official installation guide](https://docs.bazzite.gg/General/Installation_Guide/install-guide/)
- [Official Secure Boot guide](https://docs.bazzite.gg/General/Installation_Guide/secure_boot/)
- [Bazzite documentation](https://docs.bazzite.gg/)

This is an independent community guide, not an official Bazzite or Universal Blue project. Screens and hardware support can change. Linked external resources may contain commands; this repository contains documentation only.

## License
Copyright © 2026 Deshaun Fowlkes (DeshaunDoesTech).

Original documentation is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). See [LICENSE](LICENSE). This allows sharing and adaptation, including commercial use, with attribution and notice of changes. Third-party materials retain their own terms.
