# Home Lab

A from-scratch home lab built on Proxmox VE and modeled on Microsoft Azure's hub-and-spoke network design. An OPNsense firewall plays the hub, with segmented VLANs as spokes for management, servers and clients. On top of that the lab runs an Active Directory domain, a Linux server, a Wazuh SIEM with attack testing, and a hybrid link to Azure. Each phase is documented below with what I built, the commands I ran, redacted screenshots, and every problem I hit and how I fixed it. The lab supports my B.S. in Cloud and Network Engineering (Azure).

## Phases

| # | Phase | Write-up | Status |
| --- | --- | --- | --- |
| 0 | Planning: goals, budget, parts list | [00-planning.md](docs/00-planning.md) | In progress |
| 1 | Hardware prep | [01-hardware.md](docs/01-hardware.md) | Planned |
| 2 | Install Proxmox VE | [02-proxmox-install.md](docs/02-proxmox-install.md) | Planned |
| 3 | Network segmentation with OPNsense (VLANs, firewall rules) | [03-network-vlans-firewall.md](docs/03-network-vlans-firewall.md) | Planned |
| 4 | Active Directory domain | [04-active-directory.md](docs/04-active-directory.md) | Planned |
| 5 | Linux server | [05-linux-server.md](docs/05-linux-server.md) | Planned |
| 6 | Wazuh SIEM and attack testing | [06-wazuh-siem.md](docs/06-wazuh-siem.md) | Planned |
| 7 | Azure hybrid cloud | [07-azure-hybrid.md](docs/07-azure-hybrid.md) | Planned |
| 8 | Backups, hardening and automation | [08-backups-hardening.md](docs/08-backups-hardening.md) | Planned |

## Repository layout

```text
homelab/
  README.md            what the lab is, diagram, skills, links to each phase
  docs/                one write-up per phase
  diagrams/            network diagram exports (draw.io)
  screenshots/         redacted screenshots, named by phase
  configs/             sanitized config files and scripts
  troubleshooting.md   every problem I hit and how I fixed it
```

## Network diagram

![Network wiring and VLANs](diagrams/02-network-wiring-vlans.svg)

More drawings (rack layout, power and safe shutdown, build steps) are in [diagrams/](diagrams/).

## Related

- [Learning roadmap](https://github.com/BlakerAtchley/roadmap)

## License

[MIT](LICENSE)
