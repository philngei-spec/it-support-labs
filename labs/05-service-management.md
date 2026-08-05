# Lab 05 - Service Management

## Objective

Learn how to manage Windows services by viewing their status, understanding startup types, restarting a service, and verifying its operation using both the Services console and the Command Prompt.

---

## Problem

A common IT support task is troubleshooting Windows services when users experience issues. This lab focused on managing the Print Spooler service, which is responsible for handling print jobs.

---

## Steps Performed

### Step 1

Opened the Services console by pressing Windows + R, typing:
services.msc

and pressing Enter.

### Step 2

Located the Print Spooler service in the list of Windows services.

### Step 3

Verified that the service was configured with:

- Status: Running
- Startup Type: Automatic

### Step 4

Opened the service properties and restarted the Print Spooler service.

### Step 5

Opened Command Prompt as Administrator.

### Step 6

Ran the following command to verify the service status:
sc query spooler

---

## Verification

Verified that the Print Spooler service was running after the restart.

The following command was used:

```cmd
sc query spooler
```

The output confirmed:

```text
STATE              : 4  RUNNING
```

---

## Troubleshooting Steps

No troubleshooting was required. The Print Spooler service restarted successfully and its status was verified using the sc query spooler command.

---

## Result

Successfully viewed, restarted, and verified the Print Spooler service using both the Windows Services console and the Command Prompt.

---

## Skills Demonstrated

- Windows Service Management
- Windows Services Console
- Command Prompt
- Service Verification
- Troubleshooting
- Windows Server Administration
- Technical Documentation

---

## Tools Used

- Windows Server 2025
- Services Console (`services.msc`)
- Command Prompt
- VMware Workstation
- Visual Studio Code
- Git
- GitHub