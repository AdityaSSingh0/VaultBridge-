# VaultBridge

## 🔐 Encrypted File Transfer Made Simple

**VaultBridge** is a lightweight, cross-platform file-sharing application built by **0x4m4**, designed to safeguard your files during transfer over networks. With robust encryption and a user-friendly GUI, VaultBridge ensures your data remains private, encrypted, and accessible only by the intended recipient.

---

### ✨ Features

- **AES-256 Encryption**  
  Strong symmetric encryption to secure file contents.

- **PBKDF2 Key Derivation**  
  Converts passwords into cryptographic keys using salting and multiple iterations.

- **Tkinter GUI Interface**  
  A clean, intuitive interface built with Tkinter for ease of use.

- **File Metadata Preservation**  
  Keeps original file names and ensures data integrity throughout the transfer.

---

### ⚙️ Requirements

To run VaultBridge, make sure you have:

- Python 3.x installed
- The following Python libraries:
  - `cryptography`
  - `socket` (included in Python)
  - `tkinter` (usually pre-installed)

### Installation

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/AdityaSSingh0/VaultBridge-.git
    cd VaultBridge
    ```

2. **Install the Required Libraries**:
    ```sh
    pip install cryptography
    ```
    ```sh
    pip install socket
    ```
    ```sh
    pip install tkinter
    ```

### Usage

1. **Run the Tool**:
    ```sh
    python VaultBridge.py
    ```

2. **Sending a File**:
    - Open **VaultBridge** and select "Send".
    - Enter the recipient's host address and port.
    - Choose the file you want to send.
    - Enter a secure password.
    - Click "Execute" to send the file.

3. **Receiving a File**:
    - Open **VaultBridge** and select "Receive".
    - Enter the port to listen on.
    - Enter the password that the sender will use.
    - Click "Execute" to start listening for incoming files.

### Example Usage

#### Sending a File:

1. Start the **VaultBridge** tool.
2. Select "Send".
3. Enter the recipient's host (e.g., `192.168.1.4`).
4. Enter the port (e.g., `12345`).
5. Choose the file you want to send.
6. Enter a secure password (e.g., `mypassword`).
7. Click "Execute".

#### Receiving a File:

1. Start the **VaultBridge** tool.
2. Select "Receive".
3. Enter the port (e.g., `12345`).
4. Enter the same password used by the sender (e.g., `mypassword`).
5. Click "Execute".

Both sides must use the same port and password. Ensure firewalls or antivirus software allow the communication.

### Security

**VaultBridge** employs several security mechanisms to ensure your files are safe:

- **AES-256 Encryption**: Strong encryption standard to protect your files.
- **PBKDF2 with HMAC-SHA256**: Robust key derivation function to secure your password.
- **IV (Initialization Vector)**: Random IV for each encryption session to ensure uniqueness.


### Disclaimer

**VaultBridge** provides strong encryption and secure communication channels, but its effectiveness depends on user practices:

Always use a strong and unique password.

Never share passwords over insecure channels.

Avoid transferring sensitive files over untrusted networks like public Wi-Fi.

**VaultBridge** does not upload or store files — everything is processed securely on your own device.

### Contact

For any issues, suggestions, or contributions, feel free to reach out or create an issue in the GitHub repository.
Have questions, ideas, or feedback?

📧 Email: singh.adirishi@gmail.com

🐞 Report issues: GitHub Issues

💻 Project repo: https://github.com/AdityaSSingh0/VaultBridge-.git

---

Thank you for using **VaultBridge**. Secure your file transfers with confidence!

- **singh.adirishi@gmail.com**
