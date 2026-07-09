🛠️ SEANS 3 – Yazılımcıların Kullandığı Araçlar
Giriş
Arkadaşlar, geçen iki derste yazılım dünyasından, Python'dan ve kendinize nasıl bir yol çizebileceğinizden bahsettik.
Ama belki şu soruyu soruyorsunuz:
"Tamam da yazılımcılar gün boyunca ne kullanıyor?"
İlginç olan şu:
Bir yazılımcı gününün çoğunu aslında Python yazmakla geçirmiyor.
Kod editörleri kullanıyor.
Dokümantasyon okuyor.
GitHub'a bakıyor.
Terminal açıyor.
Hata araştırıyor.
Yani yazılım sadece programlama dilinden oluşmuyor.
Bugün biraz bu araçlardan bahsedeceğiz.

Bölüm 1 – VS Code ve PyCharm
(Ekranda ikisini yan yana gösteriyorum.)
Şimdi size iki uygulama göstereceğim.
VS Code.
Ve PyCharm.
Yeni başlayanların en çok karıştırdığı şeylerden biri budur.
Çünkü kurslarda genellikle şöyle olur:
"Hadi VS Code kuruyoruz."
Ve konu kapanır.
Ama kimse şunu anlatmaz:
Bu uygulamalar neden var? Birbirinden farkı ne?
İlk olarak bir kavram öğrenelim.

Kod Editörü
Kod editörü aslında gelişmiş bir not defteridir.
Ama yazılımcılar için hazırlanmıştır.
Kodları renklendirir.
Hataları gösterir.
Dosyaları düzenler.
VS Code buna örnek verilebilir.

IDE
Şimdi ikinci kavram.
IDE.
Integrated Development Environment.
Yani Geliştirme Ortamı.
Bunu bir atölyeye benzetebiliriz.
Kod editörü sadece masaysa, IDE bütün atölyedir.
İçinde araçlar vardır, hata ayıklama vardır, proje yönetimi vardır, test sistemleri vardır.
PyCharm bunun güzel örneklerinden biridir.

Şimdi önemli soru:
VS Code editör, PyCharm IDE — peki ikisi arasında hangisini kullanacağız?
Aslında bu ayrım o kadar keskin değil.
VS Code başlangıçta bir editör.
Ama eklenti eklediğinizde IDE'ye çok yaklaşıyor.
(Ekranda eklenti panelini gösteriyorum.)
Mesela ben web geliştirirken — JavaScript, HTML, CSS yazarken — VS Code'u kullanıyorum.
Çünkü Live Server gibi eklentiler çok güzel çalışıyor.
Değişiklik yaptığınızda tarayıcı anında yenileniyor.
Bu tür şeyler için VS Code ekosistemi çok olgun.

PyCharm ise özellikle Python projeleri için daha derin bir anlayışa sahip.
Büyük projelerde projenin tamamını "görüyor" gibi davranıyor.
Ama ikisi de işinizi görür, gerçekten.
İnternette bazen savaş çıkar.
"VS Code daha iyi."
"Hayır PyCharm daha iyi."
Ben size ikisinin mantığını anlatıyorum.
Araçtan korkmamanız için.

Küçük Bir Not: Parameter Hints
(Ekranda gösteriyorum.)
Şimdi her iki araçta da şunu göreceksiniz:
Bir fonksiyon yazıp parantez açtığınızda, üstte küçük bir şey belirebiliyor.
(Pycharm somut örneğini gösteriyorum)
topla(a, b, c)
gibi.
Bu otomatik kod tamamlama değil.
Bu, o fonksiyonun ne beklediğini size hatırlatıyor.
Buna "parameter hint" ya da "signature help" deniyor.
Çok işe yarıyor. Bir fonksiyonun kaç parametre aldığını ezberlemenize gerek kalmıyor.

Bölüm 2 – Anaconda: Altta Ne Var?
Şimdi bir soru sorayım.
Bazı kurslar şunu söyler:
"VS Code'u kur. PyCharm'ı kur. Anaconda Navigator'ı kur."
Ve siz de kurarsınız.
Sonra PyCharm'ı açıyorsunuz, içinde Jupyter Notebook var.
VS Code'u açıyorsunuz, orada da Jupyter Notebook var.
Aklınıza şu geliyor:
"Abi bunlar hep aynı şeyi mi yapıyor? Neden üç tane kurdum?"
Güzel soru.

Cevap şu: Anaconda bir dağıtım.
Yani Python'ı tek başına kurmak yerine, Anaconda kurunca şunların hepsi geliyor:
* Python
* Jupyter Notebook
* Veri bilimi için onlarca hazır paket
* Anaconda Navigator adında bir yönetim arayüzü
Anaconda Navigator ise bunları yönetmek için grafik bir ekran.
"Jupyter'ı başlat, Spyder'ı aç" gibi şeyleri tıklayarak yapıyorsunuz.

Peki PyCharm'daki Jupyter nereden geliyor?
PyCharm kendi Jupyter'ını getirmiyor.
Bilgisayarınızda Anaconda kuruluysa, oradan kullanıyor.
VS Code da aynı şekilde davranıyor.
Yani Anaconda altyapı gibi.
VS Code ve PyCharm ise o altyapının üstünde çalışan arayüzler.

Peki hepsini kurmak gerekiyor muydu?
Teknik olarak hayır.
Sadece Anaconda kurulsa, Jupyter ve Spyder zaten içinde geliyor.
Ama kurslar genellikle "herkes farklı araç kullanacak, hepsini tanısınlar" diye hepsini gösteriyor.
Siz şimdi neden kurduğunuzu anlıyorsunuz.
Bu bile büyük fark.

Bölüm 3 – Jupyter Notebook
(Ekranda Notebook gösteriyorum.)
Peki bu nedir?
Bu da başka bir araç.
Adı: Jupyter Notebook.
İlk gördüğümde ben de şaşırmıştım.
Çünkü normal editörlere benzemiyor.
Kod yazıyorsunuz.
Çalıştırıyorsunuz.
Sonucu hemen altında görüyorsunuz.
Biraz laboratuvar defteri gibi.

Ama şunu dikkat edin.
Jupyter'ın çalışma mantığı biraz farklı.
Normal bir Python dosyasında kod baştan sona çalışır.
Jupyter'da ise "hücre" dediğimiz parçalar var.
Her hücreyi ayrı ayrı çalıştırabiliyorsunuz.
Ve hücreler birbirinin değişkenlerini paylaşıyor.
Yani üstte tanımladığınız bir şeyi altta kullanabiliyorsunuz.
Bu çok pratik.
Ama bazen hücreleri karışık sırayla çalıştırırsanız beklenmedik sonuçlar çıkabiliyor.
Bu yüzden bazıları Jupyter'ı "farklı bir dil" gibi tarif ediyor — dil aynı, ama çalışma mantığı farklı.

Özellikle:
* Veri bilimi
* Yapay zekâ
* Veri analizi
alanlarında çok kullanılır.
Yapay zekâ tarafına yönelirseniz sık sık göreceksiniz.

Bölüm 4 – Terminal
(Basit terminal ekranı açıyorum.)
Şimdi çoğu kişinin korktuğu yere geldik.
Terminal.
Filmlerde hackerların kullandığı siyah ekran.
Ama sizi rahatlatayım.
Terminal hacker olmak için yapılmadı.
Bilgisayarla doğrudan konuşmak için yapıldı.
Grafik arayüzlerden önce insanlar bilgisayarları böyle kullanıyordu.

Terminalin ilginç bir tarafı var.
Çok hızlı.
Bir klasöre gitmek, bir program çalıştırmak, bir şey yüklemek — hepsi birkaç kelimeyle oluyor.
Ve bu hız bazen eğlenceli bile geliyor.

Ama bir şeyi de söyleyeyim.
Terminal tehlikeli olabilir.
Grafik arayüzde bir şeyi silmeye kalktığınızda bilgisayar sorar:
"Silmek istediğinize emin misiniz?"
Terminalde sormaz.
Verdiğiniz komutu doğrudan çalıştırır.
Bu yüzden internetten kopyaladığınız bir terminal komutunu körü körüne çalıştırmamak gerekir.
Ne yaptığını anlamadan çalıştırmayın.

Şu an öğrenmeniz gerekmiyor.
Ama görünce yabancılık çekmeyin istiyorum.

Bölüm 5 – GitHub
(GitHub'ı açıyorum — kendi depom açık.)
Şimdi geldik benim favori platformuma.
GitHub.
GitHub'ı biraz erken anlattığımı düşünebilirsiniz.
Çünkü çoğu kurs çok daha sonra bahsediyor.
Ama ben erkenden duymanızı istedim.
Çünkü GitHub bana göre yazılım dünyasının sosyal ağı gibi.
Burada insanlar kod paylaşıyor, proje geliştiriyor, birbirlerine katkı sağlıyor, açık kaynak projeler üretiyor.

(Katkı tablosunu gösteriyorum.)
Şu yeşil karelere bakın.
Bu benim katkı tablom.
Her kare bir gün.
Her koyu yeşil, o gün bir şeyler yaptığımı gösteriyor.

Ama şunu söyleyeyim:
Bu kareler sadece kod yazmakla dolmuyor.
Bir README düzenlemek.
Bir hata bildirmek.
Bir dökümana cümle eklemek.
Bunların hepsi katkı sayılıyor.
Yani GitHub'a katkıda bulunmak için üst düzey yazılımcı olmak gerekmiyor.

Commit Mantığı
(Commit geçmişini gösteriyorum.)
Şimdi burada şunu görüyorsunuz.
Her değişikliğin bir mesajı var.
Buna "commit" deniyor.
Ve commit mesajları genellikle emir kipiyle yazılıyor.
"Düzelttim" değil, "Düzelt."
"Ekledim" değil, "Ekle."
İngilizce'de "Fixed" değil "Fix."
Bunun nedeni şu:
Commit mesajı "Ben ne yaptım?" sorusunu değil, "Bu commit ne yapar?" sorusunu cevaplıyor.
Küçük bir fark ama yazılım dünyasında herkes buna uyuyor.

Birlikte Çalışmak
(Depo ayarlarını açıyorum.)
Şimdi size bir şey göstereceğim.
GitHub'da birine "katkıda bulunan" olarak ekleyebiliyorsunuz.
Bir tıklamayla.
Ve o andan itibaren aynı depoda birlikte çalışabiliyorsunuz.
Biri bir şey değiştiriyor, diğeri görüyor.
Biri hata buluyor, diğeri düzeltiyor.
İşte yazılım dünyasında ekip çalışması böyle işliyor.

Peki GitHub neden önemli?
Bir gün bir web sitesi yapacaksınız.
Bir oyun geliştireceksiniz.
Bir TÜBİTAK projesi hazırlayacaksınız.
Ve bunları gösterebileceğiniz bir yere ihtiyacınız olacak.
İşte GitHub burada devreye giriyor.
Üniversiteler, takımlar, kulüpler — ürettiklerinizi burada görebiliyor.

Bölüm 6 – Gerçek Bir Yazılımcının Masası
Şimdi fark etmiş olabilirsiniz.
Bir yazılımcının kullandığı şey sadece Python değil.
Bir yazılımcının masasında genellikle şunlar bulunur:
* VS Code veya PyCharm
* Anaconda (altyapı olarak)
* Tarayıcı
* GitHub
* Terminal
* Dokümantasyon
* Yapay zekâ araçları
Yani yazılım aslında bir ekosistemdir.