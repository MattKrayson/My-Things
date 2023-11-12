# Proxmox Commands
- **[Proxmox Docss](https://pve.proxmox.com/pve-docs)**
- **[Proxmox Download](https://www.proxmox.com/en)**

**Proxmox low power mode**
```
echo "powersave" | tee /sys/devices/system/cpu/cpu*/cpufreq/scaling_governor
```