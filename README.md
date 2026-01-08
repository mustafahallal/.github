
# 👋 mustafahallal'a Hoş Geldiniz!

Burası yaratıcılığın kodla buluştuğu yer. **mustafahallal** çatısı altında yenilikçi çözümler geliştiriyor, açık kaynak dünyasına katkı sağlıyor ve sürekli öğreniyoruz.

---

## 📊 Organizasyon Genel Bakış

Aşağıda organizasyon aktivitelerini gösteren görsel yer alır. (Görsel .github/workflows/metrics.yml tarafından üretilir.)

![Organization Metrics](https://raw.githubusercontent.com/mustafahallal/.github/main/github-metrics.svg)

> Not: Organizasyondaki birçok repo `private` görünüyor. Eğer metrics görselinde özel repo istatistiklerini görmek istiyorsan:
> - METRICS_TOKEN secret'ına repo (ve gerekiyorsa read:org) izinleri ver.
> - Private repoların verisini almak için token `repo` scope içermelidir. Public-only veriler için `public_repo` + `read:org` da çalışabilir ama private için `repo` gerekir.

---

## 🚀 Neler Yapıyoruz?
- 🛠️ Yazılım Mimarileri: Ölçeklenebilir ve temiz kod yapıları  
- 🌐 Web Teknolojileri: Modern frontend ve backend çözümleri  
- 📱 Mobil Deneyimler: Kullanıcı odaklı uygulama geliştirme

---

## ✨ Katkıda Bulunma (Hızlı Rehber)
1. İlgilendiğiniz bir issue seçin.  
2. Repo'yu fork'layın.  
3. Yeni bir branch oluşturun (örn. `feature/my-feature`).  
4. Değişikliklerinizi test edip PR açın.

---

## 🔐 METRICS için Gerekenler & Güvenlik
- Repository veya Organization secrets içinde `METRICS_TOKEN` oluştur:
  - Eğer organizasyon private repoları dahil etmek istiyorsa PAT (Personal Access Token) oluştururken `repo` scope ekle.
  - Organizasyon meta verilerine erişim gerekiyorsa `read:org` eklenmeli.
- Güvenlik önerisi: action'ları `@latest` ile değil tag/sha ile pin'le (biz örnekte v3.34.0 kullandık).
- Eğer SVG görünmüyor veya hata mesajı alıyorsan Actions log'unu kontrol et; özellikle log'da "Unsupported context organization" hatası varsa `plugin_isocalendar` kapalı mı diye bak.

---

## Repos (kısa)
Organizasyondaki repoların bir kısmı private olduğundan, herkese açık badge/istatistikler doğrudan görünmeyebilir. Örnek repo listeni göz önüne alarak (örn: news, newCrmBackend, ret, Financio, trors, server, temp, Router, ServerMain, status vs.):
- Metrics görseli token izinleriyle birlikte private repoları da çekebilecektir.
- README içerisindeki repo-spesifik badge'leri kullanmak istiyorsan her badge için hedef repo adını doğru gir (ör. `mustafahallal/news`). Private repo badge'leri public olarak erişilemez.

---

## İletişim
Bakımcı: @mustafahallal  
E-posta: (buraya iletişim bilgisi ekle)
```
