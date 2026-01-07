# 🚀 Outlook Lite Checker (Protected Version)

A high-performance Outlook Lite connection checker. This version is encrypted and protected for security and privacy.

### 🛠️ Prerequisites
This tool is specifically designed to run within the **Termux** environment on Android. Running it from shared storage (like /sdcard/Download) may cause permission errors.

### 📥 Installation & Usage

Copy and paste the following commands into your Termux terminal:

```bash
# 1. Update system and install required tools
pkg update && pkg upgrade -y
pkg install python git clang -y

# 2. Clone the repository
git clone [https://github.com/fang3yuan/Checker.git](https://github.com/fang3yuan/Checker.git)
cd Checker

# 3. Install necessary python libraries
pip install requests

# 4. Grant execution permissions to the encrypted binary
chmod +x ajnbe.cpython-312.so

# 5. Run the tool
python mine.py

