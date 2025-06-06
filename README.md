# SSH Reverse Port Forwarder with Paramiko

This Python script creates a **reverse SSH tunnel** using the `paramiko` library. It allows a remote server to forward traffic back to a local machine through a secure SSH connection — useful for accessing services behind NAT or firewalls.

---

## 🚀 Features

- Secure reverse port forwarding using SSH
- Threaded tunnel handler for handling multiple connections
- Works without manual SSH commands — fully automated
- Written in pure Python using `paramiko` and `socket`

---

## 🛠️ Requirements

- Python 3.x
- `paramiko` library

Install dependencies:

```bash
pip install paramiko
