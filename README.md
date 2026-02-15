# From-Power-Button-to-Login-Prompt-The-Complete-Linux-Boot-Process-Explained
From Power Button to Login Prompt

The Complete Linux Boot Process Explained. Many people use Linux.
Fewer truly understand what happens between pressing the power button and seeing the login screen.

I documented a detailed SOP explaining the complete Linux Boot Process, step by step — from hardware initialization to systemd targets.

This guide covers:

✔ Power-on and firmware execution
✔ BIOS vs UEFI architecture differences
✔ POST (hardware validation phase)
✔ How GRUB is located and loaded
✔ BIOS (MBR) vs UEFI (GPT + ESP) boot stages
✔ Kernel and initramfs loading process
✔ Driver initialization and early userspace
✔ Root filesystem mounting and /etc/fstab role
✔ PID 1 execution (systemd)
✔ Targets, services, and login initialization
