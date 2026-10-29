# Kart Masası 3D

Tek dosyalık 3D blöf kart oyunu. Tarayıcıda oyna: https://tunc-eray.github.io/p/

- Kaynak dosya: `kart-masasi-offline.html` (three.js gömülü, internet gerekmez)
- Yayın: `docs/index.html` (GitHub Pages, `main` dalı /docs)

## Yenilikler

- **Figürlere benzeyen kurbağa büyücüler**: koca, önü kalkık, ucu kıvrık kahverengi şapka (kırmızı/beyaz boya lekeleri),
  kehribar gözler + kırmızı çerçeve + dikey gözbebekleri, geniş siyah ağız, deri kuşak + toka, kafataslı asa.
- **Boyun gözü kolyesi**: her kurbağanın göğsünde altın bir kolye var; talimatını anlatırken kolyenin kapağı açılıp göz parlar,
  yüz gözleri kapanır.
- **Talimat okuma (sıra)**: parşömene tıklayınca (1) **asa kalkar**, (2) **kolye talimata doğru uçar ama gözü kapalıdır**,
  (3) oyuncunun **kendi gözleri kapanır**, (4) **kolyenin gözü açılır**, kamera kolyeye yaklaşır ve talimat o gözden
  okunur (iris + göz kapakları perdesi, `#eyev`). "Çık" deyince göz kapanır, kendi gözümüzden görmeye başlarız,
  talimat yerine döner ve kolye **yavaşça** uçmayı bırakıp yerine süzülür.
- **Asa**: artık budaklı/kırık ahşap sap (4 boğum + boğum yumruları), **deri sargılı kavrama**, gerçek **kafatası**
  (göz çukurları, kırmızı parlayan gözbebekleri, burun boşluğu, üst/alt dişler) ve kafatasından sarkan **sallanan tılsım**.
  Aynı asa hem kurbağalarda hem birinci şahıs sahnede kullanılıyor; gözleri sıra kimdeyse kırmızı yanıp sönüyor.
- **Karakterler**: dalgalı kenarlı şapka siperi + kıvrık uç + yamalı kumaş, siğiller, parmaklar, kemerde kese ve
  sarkan küçük kafatası, **gerçek göz kapağı** (deri kubbe kapanıp gözü örtüyor; artık göz ezilmiyor).
- **Kart atma**: desteden çekilen kart "Ortaya at" denince asa onu havaya kaldırır, sonra döndürerek masaya fırlatır;
  kart dizilen kartların **ilerisine** düşer (altında/arkasında kalmaz).

