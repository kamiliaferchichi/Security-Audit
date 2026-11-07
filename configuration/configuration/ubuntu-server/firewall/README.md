# UFW Firewall Configuration

## 1. Objective

Configure and verify the Ubuntu Server firewall to control incoming and outgoing network traffic.

## 2. Firewall Management Commands

```bash
sudo ufw status verbose
sudo ufw status numbered
```

## 3. Firewall Configuration Results

- Firewall: UFW
- Status: Active
- Default incoming policy: DENY
- Default outgoing policy: ALLOW

## 4. Allowed Firewall Rules

| Service | Port | Protocol | Action |
|---|---|---|---|
| SSH | 22 | TCP | ALLOW |
| HTTP | 80 | TCP | ALLOW |

Rules are applied to both IPv4 and IPv6.

## 5. Security Explanation

- Incoming connections are denied by default.
- SSH is allowed for remote server administration.
- HTTP is allowed for web server access.
- Outgoing connections are allowed.
