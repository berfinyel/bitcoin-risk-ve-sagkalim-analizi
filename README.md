# Bitcoin Zirve Dönemlerinde Ayı Piyasasına Geçiş Risk Analizi
**Yöntem:** Sağkalım (Survival) Analizi – Cox Proportional Hazards

Bu proje, finansal piyasalardaki döngüsel hareketleri tıp ve mühendislik alanlarında kullanılan **Sağkalım (Survival) Analizi** yöntemleriyle inceleyen, disiplinlerarası bir istatistiksel araştırma projesidir.

> **Proje Durumu:** Bu çalışma aktif olarak devam etmektedir. Metodolojik yaklaşım paylaşılmış olup, nihai model çıktıları ve anlamlılık katsayıları gizli tutulmaktadır.

## Araştırma Sorusu
*"Bitcoin (BTC) yeni bir rekor (zirve) kırdıktan sonra, hangi piyasa koşulları altında %20'lik değer kaybı yaşayarak ayı piyasasına (Bear Market) girer? Bu zirvelerin hayatta kalma süresini etkileyen temel faktörler nelerdir?"*

*   **Zaman Çerçevesi:** 2017 - Nisan 2026 günlük verileri.
*   **Model Yapısı:** 555 adet izole edilmiş zirve periyodu ve %8.1'lik "Nadir Olay (Rare Event)" oranı.

## Sağkalım Analizi ve Finansal Kavramlar
Bu modelde Bitcoin zirveleri yaşayan birer organizma olarak ele alınmıştır:
*   **Ölüm (Event):** Zirve değerinin %20 altına inilmesi (Ayı piyasasının başlaması).
*   **Hayatta Kalma (Right Censoring):** Fiyatın %20 düşmeden daha yüksek yeni bir zirve oluşturarak mevcut zirveyi "sansürlemesi".

## İncelenen Risk Faktörleri (Model Girdileri)
Model, zirvelerin ömrünü belirlemek için şu hipotezleri test etmektedir:

1.  **Hız ve Coşku (Return):** Hızlı oluşan zirveler daha çabuk mu çöker?
2.  **Sarsıntı (Volatilite):** Piyasadaki güvensizlik ortamı "ölüm" riskini nasıl etkiler?
3.  **Lastik Bant Etkisi (MA30 Sapması):** Fiyat ortalamadan çok uzaklaştığında geri çekilme ihtimali ne kadar artar?
4.  **Yakıt (Hacim Oranı):** Zirveye giden yolda harcanan işlem hacmi, trendin gücünü mü yoksa tükenişi mi temsil eder?
5.  **Dış Etkenler:** Hafta sonu sığ piyasa koşulları ve Halving (Arz kesintisi) döngülerinin zirve ömürlerine etkisi.

---
*Bu çalışma üzerinde veri modelleme ve analiz süreçleri aktif olarak devam etmektedir.*
