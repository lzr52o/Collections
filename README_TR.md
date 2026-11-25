[English](README_EN.md) · [简体中文](README.md) · [日本語](README_JA.md) · [한국어](README_KO.md) · Türkçe

![Quantumult X Koleksiyonu](header.png)

<div align="center">

# QuantumultX

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=0366D6&center=true&vCenter=true&width=600&lines=%E6%AC%A2%E8%BF%8E%E6%9D%A5%E5%88%B0+Quantumult+X+%E5%90%88%E9%9B%86%3B%E9%85%8D%E7%BD%AE+%C2%B7+%E8%84%9A%E6%9C%AC+%C2%B7+%E8%BF%9C%E7%A8%8B%3B%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E5%8D%B3%E5%8F%AF%E8%AE%A2%E9%98%85)

Yapılandırma · Betik · Uzaktan

![访问量](https://komarev.com/ghpvc/?username=lzr52o&color=0e75b6&style=flat)

</div>
## 📖 Kullanım Kılavuzu

QuantumultX, Quantumult X için yapılandırma ve betik koleksiyonudur: `configs/` klasöründe hazır yapılandırma dosyaları, `scripts/` klasöründe ise bunlara eşlik eden kilit açma betikleri bulunur. Bağlantıyı yapıştırarak abone olabilirsiniz; kural yazmanıza gerek yoktur.

### İçindekiler

- [Collections.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/Collections.conf): Uygulama kilit açma koleksiyonu — birçok uygulamada üyelik kilidini açan yeniden yazma kuralları.
- [revenuecat-markbuy.qx.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/revenuecat-markbuy.qx.conf): MarkBuy Pro, hepsi bir arada RevenueCat kilit açma.
- [unlock-collection.qx.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/unlock-collection.qx.conf): Kilit açma koleksiyonu, 24 betik: reklam engelleme, üyelik kilidi açma, fiyat geçmişi, Netflix puanları ve bilgi yarışması cevap yardımcısı.
- [v2ex-checkin.qx.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/v2ex-checkin.qx.conf): V2EX günlük otomatik giriş (check-in).
- [weibo-enhanced.qx.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/weibo-enhanced.qx.conf): Weibo yardımcısı — Weibo'daki reklamları ve tanıtım gönderilerini kaldırır.

`scripts/` klasöründeki 6 betik (Adapty, NotBoring, revenuecat.vip, vvebo, PhotoRetouch, TouchreTouch) tek tek uygulamaların kilit açma betikleridir. Yukarıdaki yapılandırmalara abone olunca otomatik olarak başvurulurlar, bu yüzden genellikle tek tek eklemenize gerek yoktur.

### Gerekenler

- iPhone veya iPad'de yüklü Quantumult X (App Store'da ücretli uygulama).
- GitHub'a (raw.githubusercontent.com) erişebilen bir ağ.
- Kilit açma özellikleri HTTPS şifre çözme (MITM) gerektirir: önce Quantumult X içinde sertifikayı yükleyin, ardından iOS Ayarlar → Genel → Hakkında → Sertifika Güven Ayarları bölümünden güvenin. Güvenilmezse betikler çalışmaz.

### Nasıl abone olunur

1. Yukarıdan kullanmak istediğiniz yapılandırmanın bağlantısını kopyalayın.
2. Quantumult X'i açın, sağ alttaki "Ayarlar" → "Profiller"e dokunun.
3. Sağ üstteki indirme simgesine dokunun, bağlantıyı yapıştırın ve "Tamam"a dokunun.
4. İndirme bitince yeni profile dokunarak geçiş yapın.

Yapılandırma bağlantısını Safari'de açıp paylaşım menüsünden "Quantumult X ile Aç"ı seçerek de abone olabilirsiniz.

### Tek bir betik nasıl kullanılır

1. `scripts/` klasöründe istediğiniz betiği bulun ve ham (raw) bağlantısını kopyalayın; biçimi şöyledir: `https://raw.githubusercontent.com/lzr52o/QuantumultX/master/scripts/betik-adı`.
2. Quantumult X'i açın, sağ alttaki "Ayarlar" → "Yeniden Yazma"ya dokunun.
3. Sağ üstteki "+"ya dokunarak yeni bir yeniden yazma kuralı ekleyin, betik URL'si alanına bağlantıyı yapıştırın ve kaydedin.
4. Ana ekrana dönüp "Yeniden Yazma" anahtarını açın.

### Sık sorulan sorular

- **Abone oldum ama çalışmıyor?** Üç şeyi kontrol edin: yeni profile geçtiniz mi, "Yeniden Yazma" anahtarı açık mı, sertifika yüklü ve güvenilir mi? Üçü de tamamsa uygulamayı kapatıp yeniden açın veya "Satın Alımları Geri Yükle"ye dokunup tekrar deneyin.
- **Bağlantı açılmıyor mu?** Ağınızın GitHub'a erişebildiğini doğrulayın; önce bağlantıyı Safari'de açmayı deneyin.
- **Nasıl güncellenir?** Yapılandırmalar uzaktan aboneliktir; Quantumult X'te "Profiller" bölümünde profile dokunmanız en son sürüme yenilemek için yeterlidir. Yeniden abone olmanıza gerek yoktur.
- **V2EX girişi (check-in) nasıl kullanılır?** v2ex-checkin.qx.conf'a abone olduktan sonra yapılandırmadaki `User` ifadesinden sonraki `.*` kısmını kendi V2EX kullanıcı adınızla değiştirin ve ilk seferde V2EX profil sayfanızı bir kez açarak çerezin alınmasını sağlayın. Sonrasında her gün 00:10'da otomatik olarak giriş yapar.
- **Netflix puanları görünmüyor mu?** Kilit açma koleksiyonundaki Netflix puanı için bir IMDb API anahtarı gerekir; BoxJs içinde `ImdbApikeyCacheKey` alanını doldurun.
- **Weibo reklamları gitmiyor mu?** Weibo yardımcısını kullanırken önce Quantumult X içindeki "Uyumluluk Geliştirme" anahtarını kapatın.

## ⚠️ Kullanım Bildirimi

Bu depo yalnızca kişisel öğrenme ve abonelik kullanımı içindir. **Yeniden yayınlamak, aktarmak, yeniden dağıtmak ve ticari amaçla kullanmak yasaktır.** Ayrıntılar için [LICENSE](./LICENSE) dosyasına bakın.


## 📊 İstatistikler

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=lzr52o&show_icons=true&theme=radical&custom_title=Lucky%27s%20GitHub%20Stats" width="46%" /><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lzr52o&layout=compact&theme=radical" width="50%" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=lzr52o&theme=radical" width="96%" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=lzr52o&theme=github-compact" width="100%" />

</div>

## 🛠️ Teknoloji Yığını

<div align="center">

![Skill Icons](https://skillicons.dev/icons?i=js,py,git,github,cloudflare,apple,vscode&theme=dark)

</div>

## 😄 Günün Sözü

<div align="center">

<img src="https://daily-sentence.lzr52o.workers.dev/sentence" width="440" height="140" alt="Günün sözü" />

</div>

## 🎮 Katkı Grafiği

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://contrib-rotate.lzr52o.workers.dev/rotate?theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://contrib-rotate.lzr52o.workers.dev/rotate?theme=light" />
  <img alt="Katkı grafiği" src="https://contrib-rotate.lzr52o.workers.dev/rotate?theme=light" />
</picture>

</div>


## 🙏 Teşekkürler

Bu depodaki tüm komut dosyaları ve modüller aşağıdaki orijinal yazarlara aittir. Emekleriniz için teşekkürler：

[chxm1023](https://github.com/chxm1023)、[ddgksf2013（墨鱼）](https://github.com/ddgksf2013)、[NobyDa](https://github.com/NobyDa)、[yichahucha](https://github.com/yichahucha)、[ddm1023](https://github.com/ddm1023)、[彭于晏](https://github.com/fenyaprilia)、[WeiGiegie](https://github.com/WeiGiegie)、[bin64](https://github.com/bin64)、[凉心（52Lxcloud）](https://github.com/52Lxcloud)、[Alex0510](https://github.com/Alex0510)、[Choler](https://github.com/Choler)、[chavyleung](https://github.com/chavyleung)、Liquor030、YG、[leey668](https://github.com/leey668)、[wf021325](https://github.com/wf021325)、[zmqcherish](https://github.com/zmqcherish)

## ⚠️ Sorumluluk Reddi

Bu depo yalnızca kişisel öğrenim içindir. Tüm komut dosyalarının ve modüllerin telif hakkı orijinal yazarlara aittir. Yeniden yayınlama, yansıtma, yeniden dağıtım ve ticari kullanım yasaktır. Orijinal yazar bilgilerini kaldırmayın. Herhangi bir ihlal varsa Telegram botum [@ccccccccoBot](https://t.me/ccccccccoBot) ile iletişime geçin, kaldıralım.


![Altbilgi](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer&text=Quantumult+X+%E5%90%88%E9%9B%86&fontSize=24&fontColor=ffffff)

