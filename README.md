# 🧠 Türkçe Metinlerde Duygu Analizi: İroni, Bağlam ve İnternet Dilinin Etkisi

## 📌 Proje Hakkında

Bu çalışma, Ankara Yıldırım Beyazıt Üniversitesi Büyük Veri Analistliği Programı'nın **Doğal Dil İşleme (NLP)** dersi kapsamında hazırlanmıştır.

Projenin amacı, Türkçe metinlerde duygu sınıflandırmasını incelemek ve ironi, bağlam ve internet dilinin sınıflandırma sonuçları üzerindeki etkilerini değerlendirmektir.

Çalışmada metinler pozitif, negatif ve nötr olmak üzere üç duygu sınıfında ele alınmıştır.

## 🎯 Projenin Amaçları

- Türkçe metinlerde duygu analizi gerçekleştirmek.
- Metinleri TF-IDF yöntemiyle sayısal olarak temsil etmek.
- İnsan tarafından belirlenen duygu etiketleriyle model tahminlerini karşılaştırmak.
- İroni, bağlam ve internet dilinin sınıflandırma üzerindeki etkilerini incelemek.
- Modelin hatalı tahminlerini analiz etmek.

## 📊 Veri Seti

Çalışmada 20 Türkçe metinden oluşan küçük ölçekli bir veri seti kullanılmıştır.

Metinler dört grupta incelenmiştir:

- Açık ifadeler
- İroni içeren ifadeler
- Bağlama bağlı ifadeler
- İnternet dili içeren ifadeler

Duygu etiketleri pozitif, negatif ve nötr olarak belirlenmiştir.

## ⚙️ Kullanılan Yöntemler

**Veri analizi:** Pandas ve NumPy

**Metinlerin sayısallaştırılması:** TF-IDF

**Sınıflandırma:** Lojistik Regresyon

**Model değerlendirme:** StratifiedKFold, çapraz doğrulama, doğruluk oranı ve karmaşıklık matrisi

**Görselleştirme:** Matplotlib

## 📈 Bulgular

Notebook dosyasındaki kayıtlı sonuçlara göre:

| Ölçüt | Sonuç |
|---|---|
| Metin sayısı | 20 |
| TF-IDF özellik sayısı | 92 |
| Doğru sınıflandırılan metin | 13 |
| Yanlış sınıflandırılan metin | 7 |
| Genel doğruluk oranı | %65 |

Modelin kayıtlı tahminlerinde negatif sınıfa eğilim gösterdiği görülmüştür.

Veri setinin küçük ve duygu sınıfları bakımından dengesiz olması, sonuçların genellenebilirliğini sınırlandırmaktadır.

Bu nedenle çalışma, yüksek performanslı bir sınıflandırma sistemi geliştirmekten ziyade NLP yöntemlerini uygulamalı olarak incelemeye odaklanmaktadır.

## 📂 Proje Dosyaları

- 📓 [Python Kodları](NLP_Sunum/kod/) — Jupyter Notebook uygulaması
- 📊 [Veri Seti](NLP_Sunum/veri/) — Analizde kullanılan Excel dosyası
- 📈 [Grafikler](NLP_Sunum/grafikler/) — Analiz görselleri
- 📽️ [Sunum Dosyaları](NLP_Sunum/sunum/) — PowerPoint ve PDF sunumları
- 📚 [Kaynaklar](NLP_Sunum/kullanılan%20kaynaklar%20ve%20linkler/) — Yararlanılan kaynaklar

Bu klasörler GitHub deposundaki `NLP_Sunum` dizini içerisinde bulunmaktadır.

## 🛠️ Kullanılan Teknolojiler

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 📚 Akademik Bilgiler

**Üniversite:** Ankara Yıldırım Beyazıt Üniversitesi

**Program:** Büyük Veri Analistliği

**Ders:** Doğal Dil İşleme (NLP)

**Çalışma Türü:** Akademik sunum ve uygulamalı analiz

---

*Bu proje eğitim ve araştırma amacıyla hazırlanmıştır.*
