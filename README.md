## Wkhtmltopdf for Odoo - Ubuntu 20.04 (Focal) - 64 bit

~~~
sudo apt-get install -y wkhtmltopdf

sudo wget https://github.com/wkhtmltopdf/packaging/releases/download/0.12.6-1/wkhtmltox_0.12.6-1.focal_amd64.deb

sudo dpkg -i wkhtmltox_0.12.6-1.focal_amd64.deb

sudo cp /usr/local/bin/wkhtmltopdf /usr/bin
sudo cp /usr/local/bin/wkhtmltoimage /usr/bin

service odoo restart
~~~
