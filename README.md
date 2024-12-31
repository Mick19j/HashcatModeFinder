# Hashcat Mode Finder

This Python script helps identify the hash type and suggests the appropriate **Hashcat mode** based on the detected hash. It uses the **Hashid** tool to detect the hash type and automatically suggests the most likely **Hashcat mode** to crack it.

## Features:
- Detects common hash types like MD5, SHA-1, and more using **Hashid**.
- Automatically suggests the most likely **Hashcat mode** based on the hash type.
- Simple and easy-to-use interface for users to enter their hash and get results.

## Installation:
1. Clone the repository.
2. Install required dependencies:
    ```bash
    pip install hashid
    ```
3. Run the script:
    ```bash
    python3 HashCatMode.py
    ```

## License:
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
