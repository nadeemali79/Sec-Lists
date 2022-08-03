# Windows Sandbox

Windows Sandbox provides a lightweight desktop environment to safely run applications in isolation. Software installed inside the Windows Sandbox environment remains "sandboxed" and runs separately from the host machine.

A sandbox is temporary. When it's closed, all the software and files and the state are deleted. You get a brand-new instance of the sandbox every time you open the application. Note, however, that as of Windows 11 Build 22509, your data will persist through a restart initiated from inside the virtualized environment—useful for installing applications that require the OS to reboot.

Software and applications installed on the host aren't directly available in the sandbox. If you need specific applications available inside the Windows Sandbox environment, they must be explicitly installed within the environment.

Windows Sandbox has the following properties:

Part of Windows: Everything required for this feature is included in Windows 10 Pro and Enterprise. There's no need to download a VHD.

Pristine: Every time Windows Sandbox runs, it's as clean as a brand-new installation of Windows.

Disposable: Nothing persists on the device. Everything is discarded when the user closes the application.

Secure: Uses hardware-based virtualization for kernel isolation. It relies on the Microsoft hypervisor to run a separate kernel that isolates Windows Sandbox from the host.

Efficient: Uses the integrated kernel scheduler, smart memory management, and virtual GPU.
