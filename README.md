## Wkhtmltopdf for Odoo - Ubuntu 20.04 (Focal) - 64 bit

~~~
sudo wget https://github.com/wkhtmltopdf/packaging/releases/download/0.12.6-1/wkhtmltox_0.12.6-1.focal_amd64.deb

sudo dpkg -i wkhtmltox_0.12.6-1.focal_amd64.deb

sudo cp /usr/local/bin/wkhtmltopdf /usr/bin
sudo cp /usr/local/bin/wkhtmltoimage /usr/bin

service odoo restart
~~~

## Wkhtmltopdf for Odoo - Ubuntu 18.04 (Bionic) - 64 bit

~~~
sudo wget https://github.com/wkhtmltopdf/packaging/releases/download/0.12.6-1/wkhtmltox_0.12.6-1.bionic_amd64.deb

sudo dpkg -i wkhtmltox_0.12.6-1.bionic_amd64.deb

sudo cp /usr/local/bin/wkhtmltopdf /usr/bin
sudo cp /usr/local/bin/wkhtmltoimage /usr/bin

service odoo restart
~~~
