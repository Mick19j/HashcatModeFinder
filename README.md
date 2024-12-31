# HashcatModeFinder
This Python script helps identify the hash type and suggests the appropriate Hashcat mode based on the detected hash. It uses the Hashid tool to detect the hash type and automatically suggests the most likely Hashcat mode to crack it.

Features:
Detects common hash types like MD5, SHA-1, and more using Hashid.
Automatically suggests the most likely Hashcat mode based on the hash type.
Simple and easy-to-use interface for users to enter their hash and get results.

Installation:
Clone the repository.
Install required dependencies:
pip install hashid
Run the script:
python3 HashCatMode.py
