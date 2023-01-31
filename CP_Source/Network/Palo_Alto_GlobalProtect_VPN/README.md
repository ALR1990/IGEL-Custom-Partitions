# Palo Alto GlobalProtect VPN Client (31 January)

|  CP Information |            |
|-----------------|------------|
| Package | [Palo Alto GlobalProtect VPN Client](https://docs.paloaltonetworks.com/globalprotect/5-1/globalprotect-app-user-guide/globalprotect-app-for-linux/download-and-install-the-globalprotect-app-for-linux) |
| Script Name | [gpvpn-cp-init-script.sh](build/gpvpn-cp-init-script.sh) |
| CP Mount Path | /custom/gpvpn |
| CP Size | 100M |
| IGEL OS Version (min) | 11.07.100 |
| Packaging Notes | Details can be found in the build script [build-gpvpn-cp.sh](build/build-gpvpn-cp.sh) |

**NOTES:**

- A reboot is required before the agent can start.

[userinterface.rccustom.custom_cmd_x11_final](igel/gpvpn-profile.xml)