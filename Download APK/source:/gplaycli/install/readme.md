# Solution
https://www.digitalocean.com/community/questions/how-to-install-a-specific-python-version-on-ubuntu
https://stackoverflow.com/questions/36296134/attributeerror-install-layout-when-attempting-to-install-a-package-in-a-virtual


# source:
```
# Python Environment
cd ~/dev
virtualenv -p python3.9 myenv
cd myenv/bin
source activate
pip install -U setuptools

# source:
cd ~/dev
git clone https://github.com/matlink/gplaycli.git
cd gplaycli
python3 -m pip install gplaycli
```
