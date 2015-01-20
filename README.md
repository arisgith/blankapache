########## Indonesia Jaya ##########
####################################
###file terlampir folder blankon####
####################################
###file apache__blankon.html########
###file readme.md##################
###file css_bootstrap.conf##########
###folder bootstrap#################

Keterangan Perubahan yang saya lakukan.
Relative path css, javascript dan ico.

A. Relative path css, javascript dan ico menggunakan /bootstrap/*.css <= mengarah pada folder /usr/share/apache2/blankon/bootstrap/
detail css berada didalam folder bootstrap, sejajar dengan folder js dan ico.

B. Untuk relative path javascript sama seperti folder css, berada didalam folder bootstrap dan folder bernama js.

langkah mencoba di folder anda.

1. Taruh folder bootstrap pada /usr/share/apache2.

2. Taruh file css_bootstrap.conf pada /etc/apache2/conf-available.

3. Buat link yang mengarah ke file css_bootstrap.conf dengan nama css_bootstrap.conf pada folder /etc/apache2/conf-enabled.  

4. Taruh file apache_blankon.html anda pada webserver sistem anda.

5. Jalankan.

email saya di aris.winchester@gmail.com jika ada kesulitan atau pertanyaan
