# proxmox-best-node-finder
This is a bash script to find the best node (node with most amount of free unallocated RAM).

## Usage
To use this script you will need to first change the MANAGER_IP, API_TOKEN, and MANAGEMENT_IFACE variables and match it to your Proxmox cluster's information.

## CLI command
To run it simply type in:
`./proxmox-best-node-finder`

## Verbose Mode
To run in verbose mode, use:
`./proxmox-best-node-finder -d`
or
`./proxmox-best-node-finder -debug`

