# helpdesk

Konfigürasyonlar, eklenecek satırlar:

1) C:\xampp\apache\conf\extra\httpd-vhosts

<VirtualHost *:80>
    DocumentRoot "C:/xampp/htdocs/helpdesk/public"
    ServerName helpdesk.local
</VirtualHost>

2) C:\Windows\System32\drivers\etc\hosts

  127.0.0.1	helpdesk.local
