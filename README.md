# ssh-panel
Simple Panel For Reseller SSH 

Features : <br>
1. Sistem Deposit : sekali deposit bisa create account sendiri<br>
2. Remote Server : 1 panel bisa untuk banyak server (vps)<br>
3. Check User : Reseller bisa check user yang telah dibuat<br>

<h2>Requirements</h2><br>
1. PHP 5.3.4 keatas<br>
2. libssh2-php<br>
3. MySQL-Server<br>
<br>
<br>
<b>TUTORIAL INSTALL</b> <br>

1. Install Web Server (apache2, mysql-server, phpmyadmin, php5, libssh2-php) | Alternatif : apache2 bisa menggunakan nginx | On debian : apt-get install apache2 mysql-server phpmyadmin php5 libssh2-php<br>
2. running apache & mysql server | /etc/init.d/apache2 start | /etc/init.d/mysql start <br>
3. open phpmyadmin di browser | http://domain.com/phpmyadmin | Kemudian buat database dan import file sql yang dilampirkan dalam file.<br>
4. kemudian edit file connect.php | ada didalam folder config. sesuaikan dengan informasi akses ke mysql server anda. <br>
5. open http://domain.com/admin/reg.php | lalu input username dan password admin anda<br>
6. setelah selesai hapus file reg.php untuk kemanan<br>
<br>
Catatan : untuk menambahkan user admin silahkan akses http://domain.com/admin/reg.php <br>
setelah menambahkan jangan lupa hapus file reg.php untuk keamanan
