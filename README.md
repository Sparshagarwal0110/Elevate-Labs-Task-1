# Elevate-Labs-Task-1


# Local Network SYN Port Scan

This project contains the results of a SYN scan performed on my local network using **Nmap**.

## Objective

To discover open ports on devices within the `192.168.1.0/24` subnet, helping to understand network exposure and identify potential security risks.

## Tools Used

- **Nmap** (Network Mapper)

## Scan Details

- **Command Used**:
  ```bash
  nmap -sS 192.168.1.0/24 -oN scan.txt
