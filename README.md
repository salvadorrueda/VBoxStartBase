# VBoxStartBase
This project provides a shell script that uses VBoxManage and other related commands to automate the setup and configuration of VirtualBox virtual machines with custom settings.

## Features

- Create VirtualBox VMs with specific configurations.
- Automate tasks like attaching ISO images, setting up networking, and managing snapshots.
- Easily customizable for different use cases or setups.

## Requirements

- **VirtualBox** installed on your system.
- `VBoxManage` available in your system's PATH.
- Bash shell (or compatible shell environment).

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/salvadorrueda/VBoxStartBase.git
   cd VBoxStartBase
   ```
2. Ensure the script has executable permissions:
   ```bash
   chmod +x vboxsb.sh
   ```

## Usage

1. Open the script file `vboxsb.sh` and customize the variables to match your desired VM settings, such as:
   - VM name
   - CPU and memory allocation
   - Network configurations
   - Storage and disk options
2. Run the script:
   ```bash
   ./vboxsb.sh
   ```

### Example Command

```bash
./vboxsb.sh --name "MyCustomVM" --cpus 2 --memory 4096 --disk 20G
```

## Contributions

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add feature-name"`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

## License

This project is licensed under the [GNU General Public License v3](LICENSE).

## Future Enhancements

- Support for bulk VM creation from configuration files.
- Enhanced error handling and logging.
- Integration with cloud storage for backup and ISO retrieval.

---
