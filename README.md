# wkhtml_0.0.12.5-dev
A version of  wkhtmltox with patched Qt, useful for Odoo 11 Reports on Ubuntu 18 LTS


## Installation procedure

#### 1. Download the wkthml 0.12.5
```
sudo wget https://github.com/thite/wkhtml_0.0.12.5-dev/raw/master/wkhtmltox_0.12.5-0.20180509.133.dev~a23cca3~bionic_amd64.deb
```
#### 2. Install the package
```
sudo dpkg -i wkhtmltox_0.12.5-0.20180509.133.dev~a23cca3~bionic_amd64.deb
```
#### 3. Install dependencies
```
sudo apt-get install -f
```
#### 4. Create Links in appropriate directories
```
sudo ln -s /usr/bin/wkhtmltopdf /usr/local/bin/
sudo ln -s /usr/bin/wkhtmltoimage /usr/local/bin/ 
```
