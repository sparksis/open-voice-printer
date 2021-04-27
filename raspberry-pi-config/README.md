# Raspberry Pi Configuration

## Steps

1. Image an SD Card
2. Enable SSH & Network services
   * https://www.raspberrypi.org/documentation/configuration/wireless/headless.md
   * https://www.raspberrypi.org/documentation/remote-access/ssh/README.md (Section 3)
3. Boot Raspberry Pi
4. Secure the `pi` user
5. Update/Upgrade system
   ```bash
   sudo apt update
   sudo apt upgrade -y
   ```
6. Install CUPS
   ```bash
   sudo apt install cups -y
   sudo usermod -a -G lpadmin pi
   ```

7. Configure CUPS for Network Access
   TODO: Document
   * https://serverfault.com/a/1019311


