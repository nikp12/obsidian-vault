WCD creates [[Provisioning packages]], which allow for configuration changes on the fly.
Comes with the [[Windows Assessment and Deployment Kit]]
There is no need to reimage or even reboot the machine.
Files can be given to users on a USB drive.
Provisioning packages are created as \*.ppkg files.
WCD runs very slow on VMs, so it is better to run it on a physical machine.


Steps:
1. Run the WCD
2. Create a project in Wizard or Advanced mode.
3. Name the project
4. Choose a Windows edition
5. Optionally, import a project.

WCD can be used to:
- Customize Windows settings
- Add or remove applications
- Create connection profiles (Wi-fi and VPN)
	- For Wi-fi:
	1. Create project in advanced mode
	2. Go to Runtime > ConnectivityProfiles > WLANSettings > SSID
	3. Preferably, encrypt the file since it includes secrets
- Install certificates
- Set up domain
- Upgrade the Windows edition

It can be applied via OOBE or during runtime.
- OOBE: After the first screen, tap the Windows key 5 times
- Runtime: Go to settings > Access Work or School, then Add or Remove Provisioning Package. Must be on USB method for this to work.
	- Alternatively, just double click the .ppkg files.
- Installation can be verified in event log, or by clicking “Add or Remove Provisioning Package” in Access Work or School.
