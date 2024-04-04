# CanaKit Raspberry Pi 4 Setup Guide (Headless Setup)

Welcome to the CanaKit Raspberry Pi 4 setup guide! Follow these simple steps to get your Raspberry Pi up and running with the CanaKit Starter Kit using SSH for a headless setup.

## Technologies Used:

- **Raspberry Pi 4:** A versatile single-board computer used for various projects and applications.
- **SSH (Secure Shell):** A network protocol that allows secure remote access to the Raspberry Pi's command-line interface.
- **microSD Card:** A storage device used to store the Raspberry Pi's operating system and files.
- **USB-C Power Supply:** A power adapter used to provide power to the Raspberry Pi.
- **Computer:** A remote computer (e.g., laptop or desktop) used to SSH into the Raspberry Pi.

## Items Needed:

- **CanaKit Raspberry Pi 4 Starter Kit:** Includes essential components such as the Raspberry Pi 4 board, microSD card with NOOBS and operating system pre-installed, power supply, and peripherals.
- **Computer with SSH Client:** A remote computer capable of running an SSH client to connect to the Raspberry Pi.
- **Text Editor:** Used to create the necessary files (e.g., `ssh` file) on the microSD card for enabling SSH.
- **Network Connection:** A local network connection (e.g., Ethernet) to connect the Raspberry Pi and the remote computer.

## Steps:

1. **Unbox the Kit:** Open the CanaKit Raspberry Pi 4 Starter Kit package and carefully remove all components.
2. **Insert microSD Card:** Insert the pre-loaded microSD card (included in the kit) into the Raspberry Pi's microSD card slot. NOOBS and the operating system are already installed on the microSD card.
3. **Power On the Raspberry Pi:** Connect the USB-C power supply to the Raspberry Pi and plug it into a power outlet.
4. **Discover Raspberry Pi IP Address:**
   - Use a network scanning tool or log into your router's admin interface to find the IP address assigned to the Raspberry Pi.
5. **SSH into Raspberry Pi:**
   - Open a terminal or command prompt on your remote computer.
   - Use the following command to SSH into the Raspberry Pi, replacing `<IP_Address>` with the IP address of your Raspberry Pi:

     ```bash
     ssh pi@<IP_Address>
     ```

   - When prompted, enter the default password `raspberry`. You will be logged into the Raspberry Pi via SSH.

## Troubleshooting:

- **No SSH Access:** If you're unable to SSH into the Raspberry Pi, ensure that SSH is enabled by checking the `ssh` file on the microSD card.

## Additional Resources:

- [CanaKit Raspberry Pi 4 Starter Kit User Guide](https://www.canakit.com/faq/)
- [Raspberry Pi Documentation](https://www.raspberrypi.org/documentation/)
- [Raspberry Pi Forums](https://www.raspberrypi.org/forums/)
