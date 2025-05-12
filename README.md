# 💾 Traefik Update Script
[![Static Badge](https://img.shields.io/badge/Traefik-Proxy-white?style=flat&logo=traefikproxy&logoColor=white&logoSize=auto&labelColor=black)](https://traefik.io/)
[![Static Badge](https://img.shields.io/badge/Bash-script-white?style=flat&logo=gnubash&logoColor=white&logoSize=auto&labelColor=black)](https://www.gnu.org/software/bash/)
[![Static Badge](https://img.shields.io/badge/GPL-V3-white?style=flat&logo=gnu&logoColor=white&logoSize=auto&labelColor=black)](https://www.gnu.org/licenses/gpl-3.0.en.html/)

A shell script to automate the process of updating Traefik deployments. **Important:** This script is designed to work exclusively with Traefik binary installations where Traefik is deployed in `/usr/local/bin`.

## ✨ Features

- Automated Traefik updates
- Safe deployment handling
- Rollback functionality
- Error handling and logging

### Command Options

```bash
-u  Update Traefik to latest version
-y  Auto-confirm all prompts (only applies for -u)
-r  Rollback to previous version
-c  Check current Traefik status
```

## 🚀 Quick Start

### Prerequisites
- Traefik must be installed as a binary in `/usr/local/bin`
- Script requires root privileges for updates

1. Clone this repository
2. Make the script executable:
   ```bash
   chmod +x traefik_update.sh
   ```
3. Run the script:
   ```bash
   ./traefik_update.sh
   ```

## 📝 Directory Structure

```
.
├── traefik_update.sh
├── LICENSE
└── README.md
```

## 🔍 Health Check

The script performs the following health checks:

- Traefik service status

To manually check the status:
```bash
systemctl status traefik.service
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 🆘 Support

If you encounter any issues or need support, please file an issue on the GitHub repository.

## 📄 License

This project is licensed under the GNU GENERAL PUBLIC LICENSE v3.0 - see the [LICENSE](LICENSE) file for details.
