## xServer | Apache Çoklu Proje Yönetim Sistemi

xServer, çoklu projeleri tek bir panel üzerinden yönetilmesini sağlar.

## xServer Tanıtım

[![xServer](https://github.com/mtrolab/xServer/raw/main/xserver.gif)](https://mtrolab.com)

#### Ön Yükleyici
xServer açıldığında güncel olup olmadığını kontrol eder. Eğer güncel değilde sunucu üzerindeki güncel dosyayı indirip güncel bir şekilde çalışmasını sağlar.

#### Yönetim Paneli
Server durumu, proje çalıştırma, yeni proje oluşturma gibi işlemleri yapılan ana paneldir.

#### xServer Config
xServer üzerinde web server çalışabilmesi için XAMPP serverin bilgisayarınıza kurulu olması gerekmektedir.
Bu panel üzerinden XAMPP server ana dizinini seçmelisiniz.
xServer üzerinden editörünüzü seçerek çalıştırdığınız projenin direk açılmasını sağlıyabilirsiniz.

#### Git Control Panel
Projelerinizi basit bir şekilde Git üzerinden kontrol edebileceğiniz basit bir paneldir.

## xServer Kurulumu Ve Kullanımı

xServer'in en son sürümünü indirip xServer.exe olarak basit bir şekilde çalıştırabilirsiniz.

### Gereksinimler:

* XAMPP Server (https://www.apachefriends.org/download.html)  - Sürüm farketmez

### Yapılandırma

#### xServer Config
XAMPP Folder Location => Bilgisayarınıza kurulu XAMPP Server klasörünü seçmelisiniz. (C:\xampp)
Open Project Application => Notepad++, Sublime Text, PhpStrom vb. (C:\Program Files\JetBrains\PhpStorm 2022.1.3\bin\phpstorm64.exe)

#### Git Control Panel
Git Config => Git kullanmadan önce yapınlandırmak zorundayız bu yüzden UI üzerinden kolaylıkla yapabiliriz.

Manuel Shell Kullanımı :
```shell
git config --global user.name "kullanici-adi"
git config --global user.email "eposta-adresi"
```

### Kullanımı:
xServer Yapılandırması yapıldıktan sonra rahatlıkla kullanabilirsiniz.

1. Create Project => Tek tuş yeni bir proje dosyası oluşturabilirsiniz.
2. RUN => Oluşturduğunuz projeyi seçerek projeyi başlatabilirsiniz.
3. Open Project => Seçtiğiniz editör üzerinde çalışan proje dosyaları açılır.

NOT: xServer Minimize edildiği zaman sağ al taraftaki araçların yanına simge haline dönüşeceltir.

## Lisans

The xServer is licensed under the
[GNU Lesser General Public License v3.0](https://www.gnu.org/licenses/lgpl-3.0.en.html),
also included in our repository in the `COPYING.LESSER` file.

The xServer is licensed under the
[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html), also
included in our repository in the `COPYING` file.
