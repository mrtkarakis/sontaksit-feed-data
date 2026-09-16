# sontaksit-feed-data

Son Taksit uygulamasının kur / altın / kripto / enflasyon akışı. Bu depo
yalnız **üretilen veriyi** taşır; derleyici ve cron özel `sontaksit-feed`
deposundadır. Elle düzenlenmez — her gün 06:30 UTC'de bot yazar.

- `feed.json` — güncel dosya (`schema: 1`)
- `history/YYYY-MM-DD.json` — günlük kopyalar

Yayın adresi: `https://mrtkarakis.github.io/sontaksit-feed-data/feed.json`
