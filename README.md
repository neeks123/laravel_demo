# laravel Trial Task


Steps 1

for creating Virtual Host

apache/conf/extra/httpd-vhosts.conf

Create a virtualhost file. Open “httpd-vhosts.conf” file. And copy the below lines of code

<VirtualHost *:80>
    DocumentRoot E:/php7/htdocs/laravel-demo/public
    ServerName niks.myapp.com
</VirtualHost>

<VirtualHost *:80>
    DocumentRoot E:/php7/htdocs
    ServerName localhost
</VirtualHost>


Step 2
Open C:\Windows\System32\drivers\etc\hosts

127.0.0.1       localhost
#::1             localhost
127.0.0.1       niks.myapp.com

