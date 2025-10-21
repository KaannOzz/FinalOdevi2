💹 Sharpe Oranı Hesaplama Aracı
👤 Yazar: Kaan Öz
ℹ️ Hakkında
Bu program, yatırımınızın riskine kıyasla getirisini ölçmek için Sharpe oranını hesaplar. Finansal analizlerde Sharpe oranı, bir yatırımın ne kadar verimli olduğunu anlamak için kullanılan temel bir göstergedir. 📊
Kullanıcıdan alınan bilgiler:
💰 Beklenen yatırım getirisi (%)
🏦 Risksiz faiz oranı (%)
📈 Portföyün risk seviyesi (standart sapma %)
Bu verilerle program, Sharpe oranını hesaplayıp performans durumunu size bildirir.
✨ Öne Çıkan Özellikler
🖋️ Kolay veri girişi
⚠️ Standart sapma 0 girilirse kullanıcı uyarılır ve yeniden giriş yapılması istenir
📉 Sharpe oranı hesaplaması:
Kodu kopyala

Sharpe Oranı = (Yatırım Getirisi - Risksiz Faiz) / Standart Sapma
🏆 Sharpe oranına göre performans değerlendirmesi:
< 1.0 → ❌ Düşük performans
1.0–2.0 → ✅ Ortalama performans
2.0–3.0 → 🌟 Üstün performans
≥ 3.0 → 🏅 Olağanüstü performans
🚀 Nasıl Kullanılır?
Programı derleyin ve çalıştırın:
Kodu kopyala
Bash
gcc sharpe_hesaplama.c -o sharpe
./sharpe
Ekranda istenen bilgileri girin.
Sharpe oranı ve performans değerlendirmesi otomatik olarak görüntülenecektir.
🖥️ Örnek Kullanım
Kodu kopyala

==== Sharpe Orani Hesaplama Araci ====

Yatirimin beklenen getirisini giriniz (%): 10
Risksiz faiz oranini giriniz (%): 2
Portfoyun standart sapmasini (riski) giriniz (%): 3

==== Sonuclar ====
Yatirim Getirisi      : 10.00%
Risksiz Faiz Orani    : 2.00%
Standart Sapma (Risk) : 3.00%
Sharpe Orani          : 2.67
Performans Degerlendirmesi: 🌟 Üstün performans
===========================================
📄 Lisans
Bu proje Kaan Öz tarafından hazırlanmıştır ve yalnızca eğitim amaçlı kullanılabilir. 🎓
