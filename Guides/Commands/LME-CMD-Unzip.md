[comment]: <> (
       __      _      __  __ ______ 
       \ \    | |    |  \/  |  ____|
        \ \   | |    | \  / | |__   
         > >  | |    | |\/| |  __|  
        / /   | |____| |  | | |____ 
       /_/    |______|_|  |_|______|
        ______ ______ ______ ______                    
       |______|______|______|______|
       This Guyide is made by Linux Made Easy a project made by Adam Grouse to help simply linux to find more go to
       https://magicflash67.github.io/Linux-Made-Easy/index.html
       )

# How to Use the Unzip Command on Linux

## How to Know if You Have the unzip Command

The fastest way to check is to try running it:

```bash
unzip
```

- If an error happens, you **do not** have the command properly installed.
- If usage/help info appears, then unzip should be properly installed on your system.

---

## How to Install `unzip` on Linux

- **Debian / Ubuntu**  
  ```bash
  sudo apt update && sudo apt install unzip
  ```
- **RHEL / CentOS 7**  
  ```bash
  sudo yum install unzip
  ```
- **RHEL / CentOS 8+ / Fedora**  
  ```bash
  sudo dnf install unzip
  ```
- **Arch Linux**  
  ```bash
  sudo pacman -Sy unzip
  ```
- **openSUSE**  
  ```bash
  sudo zypper install unzip
  ```
- **Alpine Linux**  
  ```bash
  doas apk add unzip
  ```
- **Gentoo**  
  ```bash
  sudo emerge --ask app-arch/unzip
  ```
- **Slackware**  
  ```bash
  sudo slackpkg update && sudo slackpkg install unzip
  ```
- **Void Linux**  
  ```bash
  sudo xbps-install -S unzip
  ```
- **Java Package Manager Supplement (Under Development)**  
  ```bash
  sudo JPM-install unzip
  ```


## How to Run the unzip Command

1. Confirm you have the unzip command or install it via JPM or your distro's package manager.
2. Type unzip in the terminal and add a space.
3. Drag your .zip file to the terminal or manually type its path.  
   **Hot Tip:** If the path contains spaces, put it in quotes. Its required when a file or file path has spaces.
4. Press **Enter**. The files will extract into your **home directory/folder**.

---
## How to Run unzip into a Custom Directory

1. Confirm you have the unzip command or install it via JPM or your distro's package manager.
2. Type unzip in the terminal and add a space.
3. Drag your .zip file to the terminal or manually type its path.
4. Add -d after the file path.
5. Drag or type the path of your custom directory.
6. Press **Enter**. The files will extract into the **specified directory**.
