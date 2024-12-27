## Introduction
This branch was developed for the first phase of Crawling Data project focused on automating the login process to the hoadondientu and thuedientu websites to collect data.

## Implemetation:
1. Download the source code from this branch in the repository.
2. Install the required libraries from the `requirements.txt` file.
3. The script has compulsory python version 3.12.4
4. Install MSSYS2 for the script hoadondientu (https://github.com/msys2/msys2-installer/releases/download/2024-12-08/msys2-x86_64-20241208.exe)

## Open a MSYS2 shell to install gtk3 runtime with this commandline, run:
1. pacman -S mingw-w64-ucrt-x86_64-gtk3
2. gcc --version

## Usage
To run the data collection script for the hoadondientu website, you need to install the necessary libraries, replace the API on the website https://anticaptcha.top/documentapi, and enter your username and password.

```python
#Replace with your generated api key on anticaptcha.top
API_KEY = "#"
```

Replace username and password equal to your current account on HoaDonDienTu. 
```python
username = "#"
password = "#"
```