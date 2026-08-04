# Lab 02 - Troubleshooting Network Connectivity

## Objective

Diagnose and resolve a Windows computer that cannot access the internet.

---

## Symptoms

- No internet connection
- Unable to browse websites
- Wi-Fi connected but no internet
- Ping requests fail

---

## Tools Used

- Command Prompt
- ipconfig
- ping
- tracert
- nslookup
- Network Settings

---

## Troubleshooting Steps

### Step 1

Checked the network adapter status in Windows Settings.

### Step 2

Ran:
ipconfig /all

Verified that the computer had a valid IP address.

### Step 3

Ran:
ping 8.8.8.8

Tested connectivity to Google's public DNS server.

### Step 4

Ran:
ping google.com

Verified DNS name resolution.

### Step 5

Ran:
tracert google.com

Checked the network path to identify where connectivity stopped.

### Step 6

Ran:
nslookup google.com

Verified DNS server functionality.

---

## Result

The computer successfully communicated with external hosts. Network connectivity and DNS resolution were functioning correctly.

---

## Skills Demonstrated

- Network troubleshooting
- IP configuration
- DNS troubleshooting
- Command-line tools
- Problem solving