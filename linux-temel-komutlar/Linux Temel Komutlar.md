Sizlere blog yazımda temel olarak kullanılan  linux  komutlarını aktaracağım. Faydalı olması dileğiyle.

# Linux Temel Komutlar

**Man**

Açılımı manual olarak geçmektedir. Man komutu sayesinde diğer komutların nasıl kullanıldığı hakkında bilgi almak için kullanılmaktadır. Ayrıca  alternatif olarak --help komutu ile kullanımını bilmediğimiz komutlar içinde kullanabiliriz.

```linux
man touch
```

yukarıda belirtilen komut ile touch komutu hakkında detaylı bilgiye ulaşabiliriz.

<hr>

**Pwd**(Print Working Directory)


Bulunduğumuz dizini öğrenmek için kullanılan komuttur.

<hr>

**Cd**(Change Directory)

Dizinler arasında geçişler için kullanılmaktadir.

- cd .. komutu ile bir üst dizine gidilir.
- cd ~ komutu ile  home dizine gidilir.

<hr>

**Ls**(List)

Dizinlere ait içerikleri görmek için kullanılmaktadır.

- ls -a komutu ile gizli dosyalar dahil diğer tüm dosyaları listeler.
- ls-lah komutu dizin altında bulanan dosyaların izinlerini, sahiplerini, boyutlarını ve oluşturma tarihleri hakkında bilgileri getirir.

<hr>

**History**


Geçmişte kullanılan komutları görüntülemek için kullanılmaktadır.

<hr>

**Clear**


Terminalde bulunan komutları silmek için kullanılmaktadır.

<hr>

**Touch**


Dosya oluşturmak için kullanılmaktadır.

```linux
touch file
```

komutu ile bizlere file adında bir dosya oluşturmaktadır.

<hr>

**Cat**

Dosya içeriğini okumak için kullanılmaktadır.

```linux
cat file
```

komutu ile bizlere file içerinde bulunan içeriği getirir. Ayrıca diğer kullanımı ise  cat  > dosyaadı verilerek bir dosya da oluşturulabilir.

<hr>

**Cp**

Dosya veya dizin kopyalamak için kullanılmaktadır.

```linux
cp files.txt  backup_files.txt
```

komutu ile files.txt içerisindekileri backup_files.txt içerisine kopyalar.

<hr>

**Mkdir**

Dizin oluşturmak için kullanılmaktadır.

```linux
mkdir test
```

komutu ile test adında dizin oluşturulabiliriz.

<hr>

**Rm**(Remove)

Dosya silmek için kullanılmaktadır.

```linux
rm test
```

komutu ile test adındaki dosyayı siler

<hr>

**Rmdir**(Remove Directory)

Dizin silmek için kullanılmaktadır.

```linux
rmdir test
```

komutu ile test adındaki dizini siler.

<hr>

**Mv**(Move)

Dosya veya dizinleri farklı bir konuma taşımak için kullanılmaktadır. Ayrıca dosya veya dizin isimlerini değiştirmek içinde kullanılmaktadır.

```linux
mv taşınılacak_dosya /gidilecekpath
```

komutu ile dosya taşıma işlemi yapılır.

```linux
mv test.txt newtest.txt
```

komutu ile test.txt dosya ismini newtest.txt  olarak değiştirme imkanı sağlamaktadır.

<hr>

**Less**


Dosya içeriğini ileri geri okumak  için kullanılan komuttur. İçeriği uzun olan dosyalar için zaman kazandırabilecek bir komuttur.

<hr>

**Head**

Dosya içeriğinin varsayılan olarak ilk on satırını göstermek için kullanılan komuttur.

<hr>

**Tail**

Dosya içeriğinin varsayılan olarak en son 10 satırını göstermek için kullanılan komuttur.

<hr>

**Grep**

Sistem içerisinde istenilen tanımı filtrelemek için grep komutunu kullanılır.

<hr>

**Find**

Dosya veya dizin aramak yapmak için find komutunu kullanılır.

<hr>

**Adduser**

Sisteme kullanıcı eklemek için kullanılan komuttur.

```linux
adduser test
```

komutu ile test adında bir kullanıcı ekledik.

<hr>

**Passwd**

Sistem kullanıcısının parolasını değiştirmek için kullanılan komuttur.

```linux
passwd test
```

komutu ile test kullanıcının parolasını değiştirebiliriz.

<hr>

**Deluser**

Sistemdeki kullanıcıyı silmek için kullanılan komuttur.

```linux
deluser test
```

komutu ile test kullanıcısını silebiliriz.

**Su**

Kullanıcı değiştirmek için kullanılan komuttur.

```linux
su kali
```

komutu ile kali kullanıcısına geçiş yapılmıştır.

**Chmod**

Dosya veya dizinlerdeki erişim haklarını değiştirmek için kullanılan komuttur.

<hr>

**Echo**

Terminal ekranına istenilen çıktıyı vermek ve dosya oluşturmak için kullanılan komuttur.

```linux
echo > test
```

komutu ile test adında bir dosya oluşturabiliriz.

**Reboot**

Sistemi kapatma işlemi  için kullanılan komuttur.

<hr>

**Uname**

İşletim sistemi hakkında bilgi veren komuttur.

- uname -a = Sistem hakkında detaylı bilgiyi verir.

<hr>

**Who**

Oturum açmış kullanıcılar hakkında bilgi veren komuttur.

<hr>

**Free**

Sistemdeki Ram hakkında  detaylı bilgi veren komuttur.

<hr>

**Nano**

Metinleri düzenlemek için kullanılan bir araçtır.Vi/vim gibi farklı metin düzenleyicilerde kullanılabilir.

<hr>

**Ps**

Sistem üzerinde çalışan processleri listelemek için kullanılan komuttur.

<hr>

**Kill**

İstemediğimiz processleri sonlandırmak için kullanılan komuttur.

```linux
kill 2250
```

komutu ile PID değeri 2250 olan process sonlandırıldı.

**Top**

Sistem üzerinde çalışan  processler hakkında bilgi almak için kullanılan komuttur.

<hr>

Blog yazımı okuduğunuz için teşekkür ederim.

Öneri ve görüşlerinizi beklerim.

[onurcoskunistanbul@gmail.com](mailto:onurcoskunistanbul@gmail.com)