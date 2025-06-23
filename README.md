# Raptor- GRUB Theme

![Raptor](https://github.com/sarojdsoka/raptor/preview.png)  
*A vibrant and modern GRUB theme inspired by neon aesthetics and a fierce dinosaur vibe.*

Welcome to **Raptor**, a custom GRUB theme designed to transform your bootloader into a visually stunning experience. This theme features a dark blue dinosaur with neon pink and purple lighting, making your boot menu look bold, attractive, and futuristic. Perfect for Garuda Linux or any other GRUB-supported system!

## Features
- **Neon Design**: Inspired by neon lights with hot pink and deep pink accents.
- **Customizable Menu**: Sleek boot menu with large, readable text and icons.
- **Progress Bar**: Dynamic countdown with a matching neon theme.
- **High Contrast**: White text on a dark background for readability.

## Preview
Since this is a GRUB theme, a live preview depends on your system. However, imagine a dark blue dinosaur roaring on a neon pink background, with a glowing "DINO BOOT ZONE" title at the top and a sleek menu below. Check the `background.png` file for a glimpse!

## Installation

### Prerequisites
- A Linux distribution with GRUB (e.g., Garuda Linux, Ubuntu, etc.).
- Basic command-line knowledge.
- Git (to clone this repository).

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/sarojdsoka/raptor
   cd raptor
    ```
2. **Copy Theme Files Move the theme folder to your GRUB themes directory:**
      ```bash
   sudo cp -r raptor /boot/grub/themes/
      ```
3. **Edit GRUB Configuration Open the GRUB config file:**
   ```bash
   sudo nano /etc/default/grub
   ```
    Add or modify the following line:
   ```bash
     GRUB_THEME="/boot/grub/themes/raptor/theme.txt"
   ```
  Save and exit (Ctrl+O, Enter, Ctrl+X).
4.**Update GRUB Run the following command to apply the theme**
  ```bash
    sudo update-grub
   ```
5.**Reboot Restart your system to see the new GRUB theme:**
