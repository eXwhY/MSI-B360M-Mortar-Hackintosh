# MSI-B360M-Mortar-Hackintosh

SMBIOS: Macmini8,1
CPU: Intel i5-8400
Motherboard: MSI B360M Mortar
GPU: UHD 630
RAM: 32GB DDR4 2600 Mhz
Wifi & Bluetooth: BCM94352HMB / DW1550
SSD: 500GB WD SN750 NVME 
OS: macOS Big Sur 11.4
OC Version: 0.7.0

Issue: When using DP Port only, screen turns black for 1-2 minutes after DSMOS but it will come back. When using DP port with HDMI (dual display) screen gets truncated for a few seconds on HDMI display and turns black on DP Display for 1-2 minutes but all will return to normal.

Previous Release only applies to hackintosh with dGPU Rx5500xt and new release for such will only be done once I have access to dgpu

This repo is for personal use only. No support is given but welcome to contribute.


Please change MLB, SystemSerialNumber, SystemUUID into your code:

```
	<dict>
		<key>AdviseFeatures</key>
		<false/>
		<key>MLB</key>
		<string>EDIT THIS</string>
		<key>MaxBIOSVersion</key>
		<false/>
		<key>ProcessorType</key>
		<integer>0</integer>
		<key>ROM</key>
		<data>
		ESIzRFVm
		</data>
		<key>SpoofVendor</key>
		<true/>
		<key>SystemMemoryStatus</key>
		<string>Auto</string>
		<key>SystemProductName</key>
		<string>iMac20,1</string>
		<key>SystemSerialNumber</key>
		<string>EDIT THIS</string>
		<key>SystemUUID</key>
		<string>EDIT THIS</string>
	</dict> 
