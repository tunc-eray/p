# Kart Masası 3D

Tek dosyalık 3D blöf kart oyunu. Tarayıcıda oyna: https://tunc-eray.github.io/p/

- Kaynak dosya: `kart-masasi-offline.html` (three.js gömülü, internet gerekmez)
- Yayın: `docs/index.html` (GitHub Pages, `main` dalı /docs)

## Yenilikler

- **Figürlere benzeyen kurbağa büyücüler**: koca, önü kalkık, ucu kıvrık kahverengi şapka (kırmızı/beyaz boya lekeleri),
  kehribar gözler + kırmızı çerçeve + dikey gözbebekleri, geniş siyah ağız, deri kuşak + toka, kafataslı asa.
- **Boyun gözü kolyesi**: her kurbağanın göğsünde altın bir kolye var; talimatını anlatırken kolyenin kapağı açılıp göz parlar,
  yüz gözleri kapanır.
- **Talimat okuma**: parşömene tıklayınca asa parşömeni kaldırır, gözler kapanır, kolyenin gözü açılır ve talimat
  "o gözün gördüğü gibi" (iris + göz kapakları perdesi, `#eyev`) okunur. Kapatınca her şey tersine döner.
- **Kart atma**: desteden çekilen kart "Ortaya at" denince asa onu havaya kaldırır, sonra döndürerek masaya fırlatır;
  kart dizilen kartların **ilerisine** düşer (altında/arkasında kalmaz).

