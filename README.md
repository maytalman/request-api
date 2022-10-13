# API ve Request Modülü

### API (uygulama programlama arayüzü ) Nedir?
- Bir uygulamanın işlevlerine dışarıdan veya uzaktan erişilip bu işlevlerin kullanılmasını sağlayan arayüzdür. API, iki uygulamanın birbiriyle iletişime geçmesini sağlayan bir yazılım aracıdır da diyebiliriz.

### API Nasıl Çalışır?

- Örneğin, cep telefonunuzdaki bir uygulamayı kullandığınızda, uygulama internete bağlanır ve verileri bir sunucuya gönderir. Ardından sunucu bu verileri alır, yorumlar, gerekli eylemleri gerçekleştirir ve telefonunuza geri gönderir. Sonrasında uygulama bu verileri yorumlar ve istediğiniz bilgiyi okunabilir bir şekilde size sunar. İşte API budur. Bunların hepsi API aracılığıyla olur.

- Google arama motorunda herhangi bir kelime aratırken, kullandığımız arayüz Google arama motorudur. Kullanılan program ise arama programıdır. Uygulama da Google’dir.

⭐Request: Bir işlem için istek

⭐Program: İsteğin gerçekleştirilmesi için programın çalışması

⭐Response: Çalışan programın yanıtı

### Request Modülü
- Python'un internetteki verilerle iletişimini sağlayan bir python modülüdür.

- HTTP requests :
    **Get** = En çok kullanılan istek türüdür. Webdeki verileri çekmenize yarar.
    **Post** = Webdeki sunucuya veri göndermenizi sağlar.
    **Put** = Mevcut bilgileri değiştirmenize yarar.
    **Delete** = Bilgileri siler.
