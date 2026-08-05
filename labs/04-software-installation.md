# Lab 04 - Software Installation & Package Management

## Objective

Demonstrate software installation and package management using both Ubuntu and Windows Server.

## Problem

Install, verify, and manage software using native package managers.

## Steps Performed

### Ubuntu

#### Step 1

Updated package lists.

```bash
sudo apt update
```

#### Step 2

Installed the `tree` package.

```bash
sudo apt install tree -y
```

#### Step 3

Verified the installation.

```bash
tree --version
``` 

### Windows Server

#### Step 4

Verified Windows Package Manager.

```cmd
winget --version
``` 

#### Step 5

Installed 7-Zip.

```cmd
winget install 7zip.7zip
```

#### Step 6

Verified installation.

```cmd
winget list 7zip
``` 

## Verification

Confirmed:
- Ubuntu package installed successfully.
- `tree --version` displayed the installed version.
- 7-Zip installed successfully using Winget.
- `winget list 7zip` confirmed the installation.

## Result

Successfully installed and verified software using Linux and Windows package managers.

## Skills Demonstrated

- Package management
- Ubuntu APT
- Windows Winget
- Software installation
- Software verification
- Documentation