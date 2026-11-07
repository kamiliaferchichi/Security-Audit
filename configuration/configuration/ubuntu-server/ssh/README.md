# SSH Service Configuration – Ubuntu Server

## 1. Objective
Document the installation, configuration and security settings of the OpenSSH service on Ubuntu Server.

## 2. Installation Commands

```bash
sudo apt update
sudo apt install openssh-server -y
```

## 3. Service Management

```bash
sudo systemctl enable ssh
sudo systemctl start ssh
```

## 4. Verification Commands

```bash
sudo systemctl status ssh
```

## 5. Configuration Results

- SSH service: Active (running)
- Automatic startup: Enabled
