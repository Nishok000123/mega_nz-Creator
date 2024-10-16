# Mega.nz Account Creator

This script automates the creation of multiple Mega.nz accounts using provided credentials. It utilizes the MegaTools binary for Linux and several Python dependencies. 

## Requirements

Before running the program, ensure you have the following:
1. **Python 3.10 or greater**

2. **MegaTools Binary (Linux Only)**
    - [MegaTools](https://megatools.megous.com/builds/builds/)

3. **Python Dependencies (Windows Only or Linux manual install)**
    - Install the required Python packages:
        - `unofficial-xitroo-api==0.9`
        - `requests` or on linux `sudo apt install python3-requests`
        - `pyside6`

## Installation

<details>
<summary><b>Linux</b></summary>
    
1. **Install MegaTools**
   
    Download and move MegaTools binary to your PATH from the official repository: [MegaTools](https://megatools.megous.com/builds/builds/)
    
2. **Clone or Download the Repository**
    
    ```bash
    git clone https://github.com/Th3K1n91/mega_nz-Creator.git
    cd mega_nz-Creator
    ```

</details>
<details>
<summary><b>Windows</b></summary>

1. **Clone or Download the Repository**
    
    ```bash
    git clone https://github.com/Th3K1n91/mega_nz-Creator.git
    cd mega_nz-Creator
    ```
    
2. **Install Python Dependencies**
    
    ```bash
    pip install unofficial-xitroo-api==0.9 requests pyside6
    ```
</details>


## Usage

To start the account creation process, run the following command for your OS:

<details>
<summary><b>Windows</b></summary>
<br>
    
```bash
python Main.py
```
or Double click start.bat
</details>


<details>
<summary><b>Linux</b></summary>
<br>
    
```bash
./start_linux.sh
```
</details>

PS.: Accounts are saved to `accounts.txt`

## Interface

![Account Creator GUI Image](https://github.com/Th3K1n91/mega_nz-Creator/blob/main/images/example.PNG)

- **Username:** Enter the desired username for the Mega.nz account.
- **Password:** Enter a secure password that meets the criteria:
    - At least 8 characters long
    - Contains at least one digit or special character
    - Includes both uppercase and lowercase letters
- **Count:** Specify the number of accounts to create.
- **Threads:** Set the number of threads to use for the account creation process.
- **Start Button:** Click to begin the account creation.

## Notes

- Ensure you comply with Mega.nz's terms of service when using this tool.
- Use responsibly and do not engage in spamming or creating accounts for malicious purposes.


## License

This project is licensed under the GNU License. See the LICENSE file for details.

## Version

- **Current Version:** 5.4.0

## Contact

For any issues or questions, please open an issue on the GitHub repository.

---

**Disclaimer:** This tool is for educational purposes only. The developers are not responsible for any misuse or damage caused by this software.
