# 💾 Traefik Update Script

A shell script to automate the process of updating Traefik configurations and deployments.

## ✨ Features

- Automated Traefik configuration updates
- Safe deployment handling
- Rollback functionality
- Error handling and logging
- Configuration validation

### Command Options

```bash
-u  Update Traefik to latest version
-y  Auto-confirm all prompts
-r  Rollback to previous version
-c  Check current Traefik status
```

## 🚀 Quick Start

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
