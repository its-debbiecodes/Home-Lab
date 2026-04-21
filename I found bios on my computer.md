# Exploring bios on my Windows 11 computer
After setting up my virtual machine, i.e., Oracle VirtualBox and Ubuntu.
I noticed, thanks to Google and curiosity, that I missed a step before installing the virtual machine.
## ENABLING VIRTUALIZATION :)

To access the BIOS on my computer
- Settings
- Systems
- Recovery
- Advanced
- Restart
Once I restarted my computer using this exact process, I came face to face with a blue screen with options.
- Troubleshoot
- UEFI settings
- System settings
  Then I looked for any texts like Intel Virtualization Technology (VT-x) OR SVM Mode (for AMD)
  Mine was Virtualization Technology (VT-x), and gladly, it was enabled. Using the F10 key, I exited BIOS successfully and restarted my computer. Now I don't need o worry about virtual computers crashing on me

