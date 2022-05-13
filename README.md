## Python Paramiko Kütüphanesi ile SSH Bağlantısı 

SSH protokolü bilindiği üzere kullanıcılara sunucularını internet üzerinden kontrol etmesini ve düzenlemesini sağlayan uzak yönetim protokolüdür.
Biz ödevimizde kendi windows bilgisayarımızdan sanal makinemiz virtualbox Ubuntu'ya bağlandık.

<br>

İlk başta virtualbox ayarlarını konfigüre ediyoruz. <br>
Bunun için virtualbox ayarlarıdan Ağ ayarlarına geliyoruz ve Şuna takıldı seçeneğini Köprü Bağdaştırıcı olararak ayarlıyoruz.

![Ağ Ayarı](https://github.com/busraakay/ForReadme/blob/master/agAyari.JPG)

Sonra Ubuntu'dan giriş yapıp terminali açıyoruz ve 
```bash
sudo -i
```
komutunu giriyouz. Burada bizden şifremizi isteyecektir. Şifremizi girdikten sonra IP adresine erişebilmek için
```bash
ifconfig
```
komutunu giriyoruz. Burada bulunan inet ve yanındaki rakamlar bize IP adresini göstermektedir.
<br><br>
![Bash](https://github.com/busraakay/ForReadme/blob/master/bash.JPG)
<br> <br>
Ubuntu'ya giriş yaptığımız kullanıcı adı, şifre ve elde ettiğimiz IP adresini artık kodlarımızda kullanabiliriz.


[Uygulama kodları için tıklayınız.](https://github.com/busraakay/ParamikoSSH/blob/master/paramiko.ipynb)
