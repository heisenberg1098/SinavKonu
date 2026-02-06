🚀 Sınav Konu Takip Sistemi
Merhaba! Bu proje, sınav dönemlerinde hangi dersten hangi konuların sorumlu olduğunu hem öğrenciler hem de öğretmenler için tek bir merkezden takip edebilmeyi sağlayan, modern ve mobil uyumlu bir web uygulamasıdır.

![sayfaTamami](https://github.com/user-attachments/assets/e3c17361-9572-4914-8fdb-882539d2b0f9)


✨ Özellikler
Dinamik Ders Listesi: Müfredatta yer alan tüm temel ve seçmeli dersler kategorize edilmiş şekilde sunulur.

Sınav Dönemi Yönetimi: Aktif sınav dönemine göre (1. Dönem 1. Yazılı vb.) konuları filtreleme ve ekleme imkanı sağlar.

Gerçek Zamanlı Veritabanı: Firebase Firestore entegrasyonu sayesinde eklenen her konu anında tüm kullanıcılarda güncellenir.

Yönetici Paneli: Sadece yetkili kişilerin konu ekleyebilmesi veya silebilmesi için şifre korumalı bir panel içerir.

Responsive Tasarım: Hem bilgisayarda hem de telefonda kusursuz çalışır.

🛠️ Nasıl Kullanılır?
1. Konu Takibi
Ana sayfada yer alan ders kartlarına tıklayarak o ders için belirlenmiş sınav konularını görebilirsiniz. Her konunun yanında hangi sınav dönemine ait olduğu belirtilir.

2. Konu Ekleme (Yönetici)
Yönetici girişi yaptıktan sonra, sayfanın üst kısmında bulunan ekleme panelini kullanarak ilgili dersi seçip konu başlığını girebilirsiniz.

![Ekleme kısmı](https://github.com/user-attachments/assets/31c9e5e2-8501-4dd4-afae-af16ec2f120c)

3. Yönetici Girişi
Sağ üst köşedeki "Giriş" butonuna tıklayarak size özel şifre ile sisteme erişebilirsiniz. Giriş yapıldığında "Yönetici Modu" aktif olur ve silme/ekleme yetkileri açılır.

<img width="653" height="390" alt="image" src="https://github.com/user-attachments/assets/adac7b1a-ea6b-4c16-a9fe-90bf0835ba5a" />

Versiyon 2.0 Geliştirmesi


Dinamik Sınav Takvimi: Artık sistem sadece konuları değil, sınav tarihlerini de takip ediyor. PDF formatındaki karmaşık sınav takvimini dijitalleştirerek, herkesin kolayca anlayabileceği bir yapıya dönüştürdüm. 

<img width="417" height="125" alt="image" src="https://github.com/user-attachments/assets/5e75997f-b40a-406f-a7a0-fc33db515b2d" />

Akıllı Sıralama Algoritması: Dersleri artık rastgele değil, sınav tarihine göre listeliyoruz. Tarihi en yakın olan sınav otomatik olarak en başa yerleşiyor, böylece "ilk neye çalışmalıyım?" sorusu anında yanıtlanıyor. 

Toplu Veri Girişi (Admin): Yönetici moduna eklediğim özel bir arayüzle, tüm sınav takvimini tek seferde, hızlıca sisteme aktarabiliyorum. Bu sayede manuel veri girişiyle zaman kaybetmiyorum.
<img width="1064" height="662" alt="image" src="https://github.com/user-attachments/assets/7963be5d-03af-483f-8a4c-a08a319c7e9d" />


Mobil Öncelikli (Responsive) Tasarım: Sınav bilgilerinin (Gün ve Saat) küçük ekranlarda ders adıyla uyumsuz görünmesini engellemek için esnek bir yapı kurdum. Bilgiler artık sığmadığında "birlikte hareket ederek" düzenli bir şekilde alt satıra geçiyor.

Firebase Entegrasyonu: Tüm veriler Firestore üzerinde gerçek zamanlı (real-time) tutuluyor. Bir veri güncellendiğinde, sayfayı yenilemeye gerek kalmadan tüm arkadaşlarımdaki liste anında güncelleniyor.


💻 Kullanılan Teknolojiler
Frontend: HTML5, CSS3 (Bootstrap 5)

Backend/Database: Firebase Firestore

Fontlar: Inter & Dancing Script (Özel imza fontu)

📝 Lisans ve Yapımcı
Bu proje tamamen tarafımdan geliştirilmiştir. Tüm hakları saklıdır.

Geliştirici: M.Enes Yalçın Yıl: 2026

## 🔗 Canlı Önizleme
Projeyi canlı olarak buradan inceleyebilirsiniz: [Sınav Takvimi Canlı Demo](https://heisenberg1098.github.io/SinavKonu/)
