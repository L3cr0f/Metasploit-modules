<h1>Metasploit Framework Modules</h1>
<h2>[bypassuac_injection_winsxs](https://github.com/rapid7/metasploit-framework/blob/master/modules/exploits/windows/local/bypassuac_injection_winsxs.rb){:target="_blank"}</h2>
<p align="justify">User Account Control (UAC) bypass module which abuses the way "WinSxS" is managed by "dccw.exe" by means of a derivative Leo's Davidson "Bypass UAC" method so as to obtain an administrator shell without prompting for consent. It supports "x86" and "x64" architectures. Moreover, it has been successfully tested on Windows 8.1 9600, Windows 10 14393, Windows 10 15031 and Windows 10 15062.</p>

<p align="justify">To configure the module you must set the proper TARGET, x64 or x86 Windows machine. Also, you must set the corresponding PAYLOAD. Finally, you must configure the common options LHOST, LPORT and so on like in any other module.</p>

<b>x86 Windows</b>
<p align="center">
<img src="https://github.com/L3cr0f/Metasploit-modules/blob/master/Pictures/Bypassuac_metasploit_windows_x86.gif">
</p>

<b>x64 Windows</b>
<p align="center">
<img src="https://github.com/L3cr0f/Metasploit-modules/blob/master/Pictures/Bypassuac_metasploit_windows_x64.gif">
</p>

For more information visit the original project repository: https://github.com/L3cr0f/DccwBypassUAC.