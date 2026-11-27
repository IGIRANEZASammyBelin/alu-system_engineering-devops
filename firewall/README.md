# Firewall

Configures the `ufw` firewall on web-01 so that all incoming traffic is blocked except TCP ports 22 (SSH), 80 (HTTP) and 443 (HTTPS).

## Files

- `0-block_all_incoming_traffic_but`: Bash script that installs ufw and sets the rules.

## Usage

Run it as root on the server:

    sudo ./0-block_all_incoming_traffic_but
