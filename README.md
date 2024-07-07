# Ticaret Stratejisi Analizi ve Backtesting

## Proje Açıklaması

Bu proje, bir ticaret stratejisinin etkinliğini değerlendirmek amacıyla geliştirilmiştir. Strateji, belirli hareketli ortalama (SMA) ve üssel hareketli ortalama (EMA) pencereleri kullanılarak oluşturulmuş ve geçmiş piyasa verileri üzerinde test edilmiştir. Proje, SMA ve EMA'nın çeşitli pencereleri kullanılarak oluşturulan stratejinin performansını değerlendirmeyi ve görselleştirmeyi amaçlamaktadır.

## Strateji Detayları

- **En İyi SMA Penceresi:** 5
- **En İyi EMA Penceresi:** 5

Bu parametreler, SMA ve EMA pencerelerinin en iyi performansı sağladığı değerlerdir. Strateji, bu pencereleri kullanarak alım ve satım sinyalleri üretmiştir. SMA ve EMA'nın birbirine göre pozisyonu alım (SMA < EMA) veya satım (SMA > EMA) sinyalleri sağlamaktadır.

## Performans Sonuçları

- **Başlangıç Sermayesi:** $1000.00
- **Son Portföy Değeri:** $1345.79
- **Kar/Zarar:** $345.79

Bu sonuç, stratejinin geçmiş veriler üzerinde başarılı bir performans gösterdiğini ve yatırımcının başlangıç sermayesini %34.58 oranında artırdığını göstermektedir.

## Görselleştirme

Stratejinin performansı zaman içinde görselleştirilmiştir. Portföy değerinin ve strateji getirilerinin zamanla nasıl değiştiği aşağıdaki grafikte gösterilmektedir:

## Kullanılan Araçlar ve Kütüphaneler

- Python
- Pandas
- NumPy
- Matplotlib

## Kurulum ve Çalıştırma

Bu proje, Python ile çalışacak şekilde tasarlanmıştır. Aşağıdaki adımları takip ederek projeyi çalıştırabilirsiniz:

1. **Gerekli Kütüphaneleri Yükleyin:**

   pip install pandas numpy matplotlib


## Gelecek Çalışmalar
Bu çalışma, kullanılan SMA ve EMA pencerelerinin strateji performansını optimize etme açısından etkili olduğunu ortaya koymaktadır. Gelecek çalışmalar, farklı pencereler ve ek göstergeler kullanarak stratejinin daha da iyileştirilmesini ve genişletilmesini hedefleyebilir. Ayrıca, stratejinin diğer piyasa koşullarında ve varlık sınıflarında nasıl performans gösterdiğini değerlendirmek için ek backtesting çalışmaları yapılabilir.

## İletişim
Herhangi bir sorunuz veya geri bildiriminiz varsa, ibrahimpuskullu44@gmail.com adresi üzerinden benimle iletişime geçebilirsiniz.

## Katkıda Bulunma
Projeye katkıda bulunmak isterseniz, pull request göndererek geliştirmelerde bulunabilirsiniz. Her türlü öneri, hata düzeltmesi veya yeni özellik eklemeleri memnuniyetle karşılanır. Lütfen katkıda bulunmadan önce katkıda bulunma kılavuzunu inceleyin.

Lisans
Bu proje MIT Lisansı altında lisanslanmıştır. Lisans detaylarını LICENSE dosyasından görebilirsiniz.

