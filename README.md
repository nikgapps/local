Steps to build NikGapps locally

Pre-requisites
1. Python 3.11 or above
2. Java 8
3. Git
4. Github account and ssh key setup


Run following commands
```
git clone https://github.com/nikgapps/local.git
```

Install NikGapps package python package (replace python3 with python.exe if on windows)
```
python3 -m pip install wheel setuptools testresources
python3 -m pip install nikgapps
```

Run following command to build NikGapps core for android 13
```
nikgapps --androidVersion 13 --packageList core
```