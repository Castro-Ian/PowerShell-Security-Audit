# PowerShell-Security-Audit

This repository contains PowerShell scripts that help detect malicious processes, suspicious files, and trigger Windows Defender scans on Windows systems.

## Features
- Detect suspicious processes based on common malware names.
- Scan common directories for suspicious files (e.g., `.exe`, `.bat`, `.ps1`).
- Run a Windows Defender quick scan if available.

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/PowerShell-Security-Audit.git
    cd PowerShell-Security-Audit
    ```

2. Run the PowerShell script:
    ```powershell
    ./MalwareDetection.ps1
    ```

3. The script will display:
   - Running processes with suspicious names.
   - Suspicious files in common directories.
   - Trigger a Windows Defender scan (if available).

## Contributing

Contributions are welcome! Please submit a pull request with detailed descriptions of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
