# 📘 Grade Calculator – Java Konsol Uygulaması

Bu proje, kullanıcının girdiği vize (%40) ve final (%60) notlarına göre ders ortalamasını, harf notunu ve kısa bir açıklamayı hesaplayan basit bir **Java konsol uygulamasıdır**. Temel Java konularını (değişkenler, karar yapıları, döngüler, switch–case) pekiştirmek için hazırlanmıştır.

---

## ✨ Özellikler

- Kullanıcıdan **ders adı**, **vize notu** ve **final notu** alır.
- Vize ve final notları için:
  - Sadece **0–100** aralığındaki değerleri kabul eder.
  - Geçersiz bir değer girilirse kullanıcıyı uyarır ve tekrar giriş ister.
- Aşağıdaki formüle göre **dönem ortalamasını** hesaplar:

  Ortalama = vize * 0.4 + final * 0.6

- Hesaplanan ortalamaya göre harf notu belirlenir:
  - AA, BA, BB, CB, CC, DC, DD, FF
- Her harf notu için kısa bir **açıklama mesajı** üretir.
- Sonuçları ekrana düzenli bir formatta yazar:
  - Ders adı
  - Vize notu
  - Final notu
  - Ortalama
  - Harf notu
  - Açıklama

---

## 🛠 Kullanılan Teknolojiler

- **Java 25** (veya sen hangi sürümü kullanıyorsan)
- **IntelliJ IDEA**
- **Git & GitHub**

---

## 📁 Proje Yapısı

- `src/Main.java` → Tüm uygulama mantığının bulunduğu ana Java sınıfı  
- `.gitignore` → Gereksiz dosyaların (örneğin derlenmiş sınıflar, IDE ayarları) repoya eklenmesini engeller  
- `README.md` → Projenin dokümantasyonu

---

## 📸 Örnek Çıktı

Aşağıda programın çalıştığında ürettiği örnek çıktı yer almaktadır:

![Program Çıktısı]<img width="296" height="343" alt="Ekran Resmi 2025-12-01 19 52 40" src="https://github.com/user-attachments/assets/a19ddac3-10d4-47ec-8126-3adfdc6753ed" />


_(Dosya adın farklıysa, buradaki `output.png` kısmını kendi yüklediğin görselin adıyla değiştir.)_

---

## 🚀 Çalıştırma

1. Projeyi IntelliJ IDEA ile aç.
2. `Main.java` dosyasını aç.
3. Üstteki **Run** (▶️) butonuna bas.
4. Konsoldaki yönergeleri takip ederek:
   - Ders adını,
   - Vize notunu,
   - Final notunu gir.
5. Sonuç ekranında:
   - Ortalama,
   - Harf notu,
   - Uygun açıklama mesajını gör.

---

## 👩‍💻 Geliştirici

**Dilara Özcan**

Bu proje, Java başlangıç seviyesini pekiştirmek ve Git/GitHub akışını pratikte denemek için oluşturulmuştur.
