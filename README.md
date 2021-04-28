# zabbix-docker-compose

Docker-compose ile temiz bir Zabbix Sunucu kurulumu amaçlanmıştır. 

Kurulum ile alakalı bilgiler nokta (.)  ile başlayan dosyalardadır. Bu dosyalarda veritabanı kullanıcı/parola bilgileri ve kurulumu özelleştirme ayarları mevcuttur.

 git clone https://github.com/farukomercakmak/zabbix-docker-compose.git

 cd  zabbix-docker-compose

 docker-compose up -d

Yukarıdaki komutların çalıştırıldığı sunucu üzerinde temiz bir kurulum gerçekleşir. Herhangi bir tarayıcı üzerinden ilgili ip adresi yazılarak;

 Kullanıcı adı: Admin
 Parola: zabbix

ile erişim sağlanabilir.

Kaynak: https://github.com/zabbix/zabbix-docker
