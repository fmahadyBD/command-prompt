# Command-prompt

![image](https://user-images.githubusercontent.com/109776849/210073212-8705b35a-ceb6-4c3a-92d0-1d56e51b05d8.png)

# Command Prompt Commands and Descriptions

The Command Prompt is a command-line interface (CLI) in Windows operating systems that allows users to enter and execute commands. It can be used for various tasks, such as troubleshooting, system maintenance, and automation.

## How to Open Command Prompt
- **Using Start Menu:** Type `cmd` in the search box and press Enter.
- **Using Run Dialog:** Press `Windows key + R`, type `cmd`, and press Enter.

Once open, you can enter commands and press Enter to execute them.

---

## Common Commands and Their Descriptions

1. **`ctrl+c`**: Stops all running programs in the Command Prompt.
2. **`dir`**: Displays the contents of the current directory.
3. **`del`**: Deletes specified files.
4. **`type`**: Displays the contents of a file.
5. **`netstat`**: Displays active network connections.
6. **`ipconfig`**: Displays the IP configuration of the system.
7. **`md`**: Creates a new directory.
8. **`rd`**: Removes a directory.
9. **`rename`**: Renames a file or directory.
10. **`time`**: Displays or sets the system time.
11. **`date`**: Displays or sets the system date.
12. **`systeminfo`**: Displays system information, such as the OS version and installed hardware.
13. **`tasklist`**: Displays a list of running tasks and their status.
14. **`taskkill`**: Terminates a running task.
15. **`echo`**: Displays a message or the value of a variable.
16. **`ping`**: Tests connectivity to a specific IP address or hostname.
17. **`sfc`**: Scans and repairs system files. Use `sfc /scannow` for a full scan.
18. **`set`**: Displays or sets environment variables.
19. **`shutdown`**: Shuts down or restarts the computer.
20. **`route`**: Displays and modifies the IP routing table.
21. **`driverquery`**: Displays a list of installed device drivers.
22. **`netdom`**: Manages domain and trust relationships.
23. **`nbtstat`**: Displays protocol statistics and current connections using NetBIOS over TCP/IP.
24. **`sc`**: Manages Windows services.
25. **`reg`**: Manages the Windows Registry.
26. **`fsutil`**: Performs various file system tasks.
27. **`diskpart`**: Manages disks, partitions, and volumes.
28. **`compact`**: Compresses or uncompresses files and folders.
29. **`robocopy`**: Copies files and directories (robust file copy).
30. **`xcopy`**: Copies files and directories, including subdirectories.
31. **`find`**: Searches for a specific text string in a file or files.
32. **`certutil`**: Manages certificates and certificate trust lists.
33. **`cipher`**: Manages encryption of files and folders.
34. **`lpksetup`**: Installs and manages language packs.
35. **`ocsetup`**: Installs and manages optional components.
36. **`pkgmgr`**: Installs and manages packages.
37. **`powercfg`**: Configures power settings.
38. **`winsat`**: Tests and displays the computer’s current performance rating.
39. **`sfc /scannow`**: Performs a full scan of the computer for bugs and system health.

---

## Explanation of Selected Commands

### `dir`
Lists the contents of the current directory.
- Usage: `dir`
- Example: `dir C:\Users`

### `ipconfig`
Displays network configuration details, such as IP address, subnet mask, and default gateway.
- Usage: `ipconfig`
- Example: `ipconfig /all`

### `ping`
Tests the connectivity to a specific address or hostname.
- Usage: `ping [address]`
- Example: `ping google.com`

### `taskkill`
Ends a task or process.
- Usage: `taskkill /IM [process_name] /F`
- Example: `taskkill /IM notepad.exe /F`

### `diskpart`
Manages disks, partitions, and volumes.
- Usage: `diskpart`
  1. Type `list disk` to display available disks.
  2. Type `select disk [number]` to choose a disk.
  3. Type `create partition primary` to create a partition.

---

## Additional Information
- **Customizing Commands:** Many commands support additional arguments and flags. Use `[command] /?` to see available options.
- **Accessing Command History:** Use the up and down arrow keys to navigate through previously entered commands.
- **Admin Privileges:** Some commands require administrative rights. Run Command Prompt as an administrator by right-clicking it and selecting "Run as administrator."

---


