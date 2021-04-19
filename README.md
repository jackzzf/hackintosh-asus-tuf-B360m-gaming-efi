# Hackintosh-EFI
Hackintosh EFI File for ASUS  B360M TUF GAMING 

# Setup
- MB: ASUS B360M TUF GAMING
- CPU: i7 8700
- GPU: NVIDIA GTX 960 2G

# BIOS Settings (BIOS Version 2811 x64)
Press F2 or Del
1. Load Optimized Defaults
2. Software Guard Extensions(SGX) -> Disabled
3. Intel(VMX) Virtualization Technology -> Enabled
4. Above 4G Decoding -> Enabled
5. IOAPIC 24-119 Entries -> Disabled
6. System Time and Alarm Source -> Legacy RTC
7. Serial Port -> Disabled
8. XHCI Hand-off -> Enabled
9. Fast Boot -> Disabled
10. Boot -> Secure Boot -> Key Management -> Clear Secure Boot Keys
11. iGPU Monitor -> Enabled

# EFI File
Install: https://github.com/secretandanon/Hackintosh-EFI/blob/main/EFI-Install.zip

Run: https://github.com/secretandanon/Hackintosh-EFI/blob/main/EFI.zip

# USB
- Please create your own UsbMap file.
- Reference: https://dortania.github.io/OpenCore-Post-Install/usb/intel-mapping/intel.html

# End
- ShowPicker -> false
- boot-args -> delete "-v"
- AppleDebug -> false
- ScanPolicy -> 17760515
