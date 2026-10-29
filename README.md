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
- **Botların gözleri** artık aniden kırpılmıyor: yumuşak kapanıp (gözbebekleri aşağı bakarak) tekrar açılıyor; talimat
  anlatırken kolyelerinin gözü açılıp parlıyor. Kolyeler büyütüldü, altın çerçeve/parıltı eklendi.
- **Kart atma**: desteden çekilen kart "Ortaya at" denince asa onu havaya kaldırır, sonra döndürerek masaya fırlatır;
  kart dizilen kartların **ilerisine** düşer (altında/arkasında kalmaz).

