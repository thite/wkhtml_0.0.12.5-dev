# wkhtml_0.0.12.5-dev
A version of  wkhtmltox with patched Qt, useful for Odoo Reports on Ubuntu 18 LTS - 

###Instead of this file now you can install wkthmltopdf from its orginital source for Odoo 11 on Ubuntu Bionic LTS. 
Go throught - [This link on Odoo.com](https://www.odoo.com/forum/help-1/question/ubuntu-18-04-lts-how-to-install-wkhtmltopdf-0-12-1-134198)

####Use the following commands:
sudo wget https://builds.wkhtmltopdf.org/0.12.1.3/wkhtmltox_0.12.1.3-1~bionic_amd64.deb </br>
sudo dpkg -i wkhtmltox_0.12.1.3-1~bionic_amd64.deb </br>
sudo apt-get install -f </br>
sudo ln -s /usr/local/bin/wkhtmltopdf /usr/bin </br>
sudo ln -s /usr/local/bin/wkhtmltoimage /usr/bin </br>
