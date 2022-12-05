# Drivers for PS4 on Nobara
Drivers for different editions of Fedora running on PS4 (PlayStation 4). Drivers include the Mesa, Libdrm and Xorg drivers necessary to properly implement Vulkan on the PS4 and have Windows games running properly.

## Installing Drivers for Nobara on PS4
1. Download the latest Release from the Releases section or the release for your version of Fedora (eg:- f35, f36, etc.).
2. Extract.
3. Change directory into 64-bit and open a terminal there.
4. Run `sudo yum reinstall *.rpm`
5. Change directory into 32-bit and open a terminal there.
6. Run `sudo yum reinstall *.rpm`

If the terminal reports a driver conflict, remove the existing drivers by following the instructions in this [YouTube video](https://www.youtube.com/watch?v=HgMa8vi--I4&t=173s).

If you need a more comprehensive and detailed tutorial, check my [blog article](https://ps4linux.com/make-ps4-linux-distro/#Step_4_Install_PS4_Linux_drivers_for_the_PS4_Linux_distro).
