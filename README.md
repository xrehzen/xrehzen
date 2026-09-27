# Rehzen

<!-- Bu dosya profilimde görünür. İlk satırları kendi cümlelerinle değiştirmek istersen buradan başla. -->

## T3 Code — Türkçe arayüz

[T3 Code](https://github.com/pingdotgg/t3code), kendi aboneliğini getirdiğin bir
arayüz: Codex, Claude Code, Cursor, Grok, OpenCode gibi aracıları tek pencerede
topluyor. Arayüzü tamamen İngilizce. Türkçe okuyan biri için eksik olan parça
tam olarak buydu, o yüzden yaptım.

- **~2.946 katalog anahtarı** çevrildi — İngilizce ve Türkçe birebir eşleşiyor,
  eksik anahtar testlerde kırılıyor
- **Türkçeye özgü düzeltmeler:** `ı`/`i` arama katlaması (`yapilandirma` yazan
  arama `Yapılandırma`'yı buluyor), Türkçe collation ile sıralama, `%50`
  biçimi, Türkçe saat
- **Electron'un kendi menüleri de Türkçe** (`tr.pak`) — quit/copy/paste/yardım
- **Sistem dili + manuel seçim** — Ayarlar → Genel → Arayüz dili

| Sürüm | İndir |
|---|---|
| [`v0.0.43-tr.2`](https://github.com/xrehzen/t3code/releases/tag/v0.0.43-tr.2) | Türkçe arayüz |
| [`v0.0.42-tr.2`](https://github.com/xrehzen/t3code/releases/tag/v0.0.42-tr.2) | İngilizce varsayılan |

Linux · AppImage (x86_64) · otomatik güncelleme çalışır

## Upstream katkısı

T3 Code topluluğu büyük lokalizasyon yükünü tek PR'da istemiyor — daha önce
benzer girişimler de kabul edilmedi. O yüzden büyük bir lokalizasyon PR'ı
atmak yerine küçük ve odaklı katkılarda bulundum:

- **[PR #13945](https://github.com/pingdotgg/t3code/pull/13945)** — arama,
  Türkçe `ı` harfini katlıyor *(açık)*
- **[#10900](https://github.com/pingdotgg/t3code/pull/10900)** ve
  **[#12563](https://github.com/pingdotgg/t3code/pull/12563)** üzerinde,
  aynı yaklaşımı paylaşan koordineli yorumlar

---

*Bu çalışma topluluk yapımıdır. T3 Code'un resmi dağıtımı değildir; Ping.gg ve
T3 Code ekibi tarafından desteklenmemektedir.*
