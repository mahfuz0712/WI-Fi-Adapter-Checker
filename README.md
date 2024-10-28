# Wi-Fi Adapter Checker

## Overview

Wi-Fi Adapter Checker is a Python application designed to check the compatibility of USB Wi-Fi adapters with Kali Linux. The software provides real-time information about the connected Wi-Fi adapter, indicating whether it is supported for hacking purposes in Kali Linux. Additionally, it can check for software updates and facilitate the downloading process.

## Features

- Detects USB Wi-Fi adapters connected to the system.
- Checks compatibility with Kali Linux based on chipset names.
- Displays the current adapter information and support status.
- Notifies users when a new version of the software is available and provides a straightforward update process.
- User-friendly GUI built using `customtkinter`.

## Requirements

- Python 3.7 or later
- Required Python packages:
  - `requests`
  - `pywin32`
  - `customtkinter`
  - `packaging`
  - `pytbangla` (if used)

You can install the required packages using pip:

```bash
pip install requests pywin32 customtkinter packaging pytbangla
```

## Installation

1. Clone the repository or download the source code:
    ```bash
    git clone https://github.com/your_github_username/Wi-Fi-Adapter-Checker.git
    cd Wi-Fi-Adapter-Checker
    ```

2. Run the application:
    ```bash
    python main.py
    ```

## Usage

1. Upon launching the application, click the "Test" button to check for connected USB Wi-Fi adapters.
2. The software will display the device name and its compatibility status.
3. If an update is available, you will be prompted to download the latest version.
4. The download progress will be shown, including the percentage and estimated remaining time.
5. Once the download completes, you can run the new executable directly.

## Configuration

To enable GitHub authentication for downloading updates, replace the `GITHUB_TOKEN` in the source code with your personal access token. You can generate a token from your GitHub account settings under Developer settings > Personal access tokens.

```python
GITHUB_TOKEN = 'your_github_token'  # Replace with your actual GitHub token
```

## Contributing

Contributions are welcome! If you would like to contribute to this project, please fork the repository and create a pull request with your improvements or fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For inquiries, please contact [Your Name] at [your_email@example.com].
