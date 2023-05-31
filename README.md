# Network Windows Commands you NEED to know

1. `ipconfig`: Displays the IP configuration information of the computer.
2. `ipconfig /all`: Shows detailed IP configuration information, including DNS settings, DHCP lease information, and more.
3. `findstr`: Searches for a specific string or pattern in the output of a command.
4. `ipconfig /release`: Releases the current IP address assigned to the computer.
5. `ipconfig /renew`: Renews the IP address of the computer by requesting a new one from the DHCP server.
6. `ipconfig /displaydns`: Displays the contents of the DNS resolver cache, which contains recent DNS resolutions.
7. `clip`: Copies the output of a command to the clipboard.
8. `ipconfig /flushdns`: Clears the DNS resolver cache and forces the computer to retrieve fresh DNS records.
9. `nslookup`: Performs DNS lookups to retrieve information about domain names, IP addresses, and more.
10. `cls`: Clears the command prompt screen.
11. `getmac /v`: Displays the MAC (Media Access Control) addresses of all network adapters on the computer.
12. `powercfg /energy`: Scans the system for energy efficiency issues and generates a detailed report.
13. `powercfg /batteryreport`: Generates a report with information about the computer's battery usage and health.
14. `assoc`: Displays or modifies file extension associations on the system.
15. `chkdsk /f`: Checks the file system of a drive for errors and attempts to fix them.
16. `chkdsk /r`: Performs a thorough scan of a drive, checks for bad sectors, and attempts recovery.
17. `sfc /scannow`: Scans system files for integrity violations and attempts to repair them.
18. `DISM /Online /Cleanup /CheckHealth`: Verifies the health of the Windows image and component store.
19. `DISM /Online /Cleanup /ScanHealth`: Scans the Windows image for component store corruption.
20. `DISM /Online /Cleanup /RestoreHealth`: Restores the Windows image from the specified source or Windows Update.
21. `tasklist`: Displays a list of running processes on the computer.
22. `taskkill`: Terminates or ends a running process or application.
23. `netsh wlan show wlanreport`: Generates a report with information about the wireless network and connectivity.
24. `netsh interface show interface`: Displays a list of network interfaces on the computer.
25. `netsh interface ip show address | findstr "IP Address"`: Retrieves the IP address information for network interfaces.
26. `netsh interface ip show dnsservers`: Displays the DNS server settings for network interfaces.
27. `netsh advfirewall set allprofiles state off`: Turns off the Windows Firewall for all network profiles.
28. `netsh advfirewall set allprofiles state on`: Turns on the Windows Firewall for all network profiles.
29. `ping`: Sends ICMP Echo Request packets to a specified network host or IP address to check connectivity.
30. `ping -t`: Continuously pings a network host or IP address until stopped.
31. `tracert`: Traces the route taken by packets from the source to a destination network host.
32. `tracert -d`: Performs a trace route without resolving host names to IP addresses.
33. `netstat`: Displays active network connections and listening ports.
34. `netstat -af`: Displays all active TCP and UDP connections, including listening ports.
35. `netstat -o`: Displays active network connections and their associated process IDs (PIDs).
36. `netstat -e -t 5`: Displays statistics for Ethernet interfaces, including TCP connections, every 5 seconds.
37. `route print`: Displays the IP routing table and routing information of the computer.
38. `route add`: Adds a static route to the IP routing table.
39. `route delete`: Deletes a static route from the IP routing table.
40. `shutdown /r /fw /f /t 0`: Shuts down and restarts the computer immediately, bypassing the firmware (BIOS/UEFI) and forcefully terminating running processes.

Credit: NetworkChuck, https://www.youtube.com/watch?v=Jfvg3CS1X3A
