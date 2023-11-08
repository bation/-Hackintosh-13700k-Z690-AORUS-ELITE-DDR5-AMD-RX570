 ![HackintoshLogo](https://camo.githubusercontent.com/917bdb01bd1b1d2366b86de67642a26baa469d59f2483ac7a345660b11249a60/68747470733a2f2f692e696d6775722e636f6d2f496673545641712e706e67)
# macOS Ventura - Hackintosh
## this is my first device installed macOS,and just installed successfull ,this efi is just for installing.And I got a rx 6950xt on the way,so  next step is …… more reboot.
---

Latest working macOS: 13.6 (22G120)

Current OpenCore: 0.9.6 MOD (binaries)
Hardware:

    CPU: Intel 13700k
        Cooling:
            Thermalright  FC140
            8x Thermalright Fans around the case for airflow
    Motherboard: Gigabyte Z690 AORUS ELITE DDR5
    GPU: AMD Radeon RX570（from rx580 2048sp downgrade vbios）
    WiFi/Bluetooth: Fenvi T919 (BCM94360[CD])
    Ethernet: Realtek RTL8125B PCI Express 2.5 Gigabit Ethernet
    RAM: 4 x 16GB @ 4800 MHz DDR5
    NVME SSD:
        1TB WD SN550 NVMe PCIe SSD (macOS)
        2TB SanDisk NVMe PCIe SSD 
    SATA SSD:
        800GB Intel S3500 SATA SSD (Windows)
    Power Supply: ApexGaming AJ850M - 850W
    PC Case: JONSBO D41 Mesh


SMBIOS: iMacPro1,1

The system dual boots macOS and Windows 10

# Install Info

Here is What you need to konw ->
[OpenCore-Install-Guide](https://dortania.github.io/OpenCore-Install-Guide/ktext.html)


# What works

    macOS Ventura
    

# What doesn't work

    Wifi

# No test (work with rursache's hardware)
    Audio
    WiFi and Bluetooth + Airdrop + Sidecar + Continuity (OOB via Fenvi T919)
    HDMI/DP (with VRR)
    Most USB ports (Capped at macOS limit of 15)
    Everything iCloud related (Drive, iMessage, FaceTime, unlock with Apple Watch, etc)
    Intel Quick Sync (if you enable iGPU in BIOS)
    Temperature monitoring
    Resizable Bar Support (enable Above 4G Decoding in BIOS)
    Update to newer macOS builds over time

# USB mapping

    [see rursache's link is bottom here](https://github.com/rursache/Hackintosh-13900k-Z690-AORUS-ELITE-AX-DDR5-AMD-6900XT)  

# Kexts

    Lilu
    Whatevergreen
    AppleALC
    VirtualSMC + SMCProcessor + SMCSuperIO
    CpuTopologyRebuild
    RestrictEvents
    CpuTscSync
    USBPorts (USBToolBox + USBMap)
    NVMeFix
    LucyRTL8125Ethernet

# Drivers

    just copy all opencore drivers

# Thanks

    [rursache](https://github.com/rursache/Hackintosh-13900k-Z690-AORUS-ELITE-AX-DDR5-AMD-6900XT)  

# Other

Markdown grammar is shit or I can't carry a 39 meters broadsword.


