I installed MacOS Monterey version 12.2 with this EFI without any problems.

INSTALLATION STEPS
First, copy the shared EFI file into the macOS Monterey USB EFI.
Open the config.plist file in the EFI with OpenCORE configurator.
In the PlatformInfo tab, select Model MacbookPro 14.1.

After this process, you will have a new Serial and UUID.

# HP-ProBook-450G5-i5-Hackintosh

OpenCore setup for running Hackintosh on HP ProBook 450 G5

##### Laptop Specifications:
- Intel Core i5 8250U CPU (KabyLake R)
- Intel UHD 620 Graphics
- 16GB DDR4 2400MHz RAM
- 15.6 Full HD IPS Display
- Synaptics I2C TouchPad
- Azureware CE123H BCM94352HMB Wi-Fi and Bluetooth Card (upgraded)
- 3 USB 3.0 Ports, 1 USB Type-C Port
- HDMI Port
- SD Card Reader
- 512GB Seagate NVME M.2 SSD (upgraded)

##### BIOS Setup:
- Disable TPM Security
- Disable Physical Presence Interface
- Disable Intel SGX
- Enable System Management Command
- Disable Fast Boot
- Disable Network PXE Boot
- Disable Power On when AC Detected
- Disable Power On when Lid is Opened
- Disable Secure Boot
- Disable Legacy Boot
- Disable Intel Optane Controller
- Enable Turbo Boost
- Enable Hyperthreading
- Enable Multi Processor
- Enable VT-x
- Disable VT-d
- Enable Turbo Boost on DC
- Enable DPTF
- Disable Media Card Reader
- Enable Runtime Power Management
- Disable Extended Idle Power States
- Enable Deep Sleep
- Disable Wake when Lid is Opened
- Disable Wake when AC is detected
- Disable Wake on USB
- Enable Power Control

##### What works:
- macOS Monterey 12.2
- Intel HD QE/CI
- HiDPI Scaled Resolution (1920 x 1080)
- USB 3.0 and USB Type-C Port
- Ethernet
- Audio on internal speaker and headphone
- Sleep and Wake
- HDMI Video and Audio
- AirPort
- Bluetooth and AirDrop
- Battery Status
- CPU Power Management
- Brightness Control Hotkeys
- Audio Control Hotkeys
- Multi-Gesture Trackpad
- Integrated Camera
- SD Card Reader (Not Tested)
##### What doesn't work:
- FingerPrint Reader


##### Thanks to:
- https://www.tonymacx86.com/threads/guide-lenovo-v330-15ikb-using-clover-uefi-hotpatch.265841/
- https://www.tonymacx86.com/threads/guide-hp-probook-elitebook-zbook-using-clover-uefi-hotpatch-10-11.189416/
- https://github.com/mmatongo/HP-450G5-Hackintosh
