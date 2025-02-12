# Hashcat Mode Finder

This Python script helps identify the hash type and suggests the appropriate **Hashcat mode** based on the detected hash. It uses the **Hashid** tool to detect the hash type and automatically suggests the most likely **Hashcat mode** to crack it.

## Features:
- Detects common hash types like MD5, SHA-1, and more using **Hashid**.
- Automatically suggests the most likely **Hashcat mode** based on the hash type.
- Displays the appropriate Hashcat command syntax ready for use.
- Simple and easy-to-use interface for users to enter their hash and get results.

## Installation:

### For Linux Users:
1. Clone the repository: git clone https://github.com/Mick19j/HashcatModeFinder.git
2. Install the required dependencies:
    ```bash
    pip install hashid
    ```
    **OR**, for Debian-based distributions like Ubuntu or Kali, you can use:
    ```bash
    sudo apt install hashid
    ```

3. Run the script:
    ```bash
    python3 HashCatMode.py
    ```

### For Windows users (using CMD or PowerShell):
1. Open **CMD** or **PowerShell** as Administrator.
2. Install **Hashid** using **pip**:
    ```bash
    pip install hashid
    ```

3. After installation, you can run the script:
    ```bash
    python3 HashCatMode.py
    ```
## Preview of Hashcat Mode Finder:
![HashCatPreview2](https://github.com/user-attachments/assets/502c8730-417e-492a-bd87-c548a6a6e8d5)

![HashCatPreview1](https://github.com/user-attachments/assets/d725de66-b010-4f17-819f-c2d47afe78b1)

## Thank You!

Thank you for checking out this repository! I hope you find the **Hashcat Mode Finder** script useful in your security and password cracking endeavors.

If you found this project helpful, feel free to ⭐️ it, fork it, or contribute by submitting a pull request. Any feedback, suggestions, or improvements are always appreciated!

Happy cracking! 🔒💻




## License:
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
