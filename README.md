<p align="center">
  <img src="https://ngc-aiot.github.io/ngcaiot_logo.png" width="600" alt="NGC-AIoT logo">
</p>

# Overview

**NGC-AIoT** is a modular platform designed to deploy and manage AIoT (Artificial Intelligence of Things) infrastructures. It provides:
- Virtualized environment (VM + LXD)
- Experiment orchestration
- Secure VPN access
- Web-based interface
- System-level device and network control

# Getting Started

Start here:

```bash
$ git clone git@github.com:ngc-aiot/ngcaiot-tools.git ./ngcaiot_tools
$ cd ngcaiot_tools
```
Use the project repository clone helper:

```bash
sudo chmod +x scripts/clone_repos_proj.sh 
```

This script has the next flags:
```text
environment: prod or dev
proto: ssh or https 
brach: main by default
```

For example, you can run: `$ ./clone_repos_proj.sh dev ssh main`

# Website

https://ngc-aiot.github.io

# Note
Some repositories manage infrastructure and networking. Ensure credentials and sensitive data are handled securely.