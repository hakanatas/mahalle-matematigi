# 🎨 Görsel Promptları — 5. Sınıf Matematik Hikayeleri

Üretilen görseller ilgili hikaye klasörünün **`assets/`** içine, buradaki dosya adıyla birebir aynı kaydedilir.

## ÜRETİM SIRASI (tutarlılık için kritik)

1. Önce `karakter_referans.png` üret.
2. Her hikaye için önce **kapak** görselini üret.
3. Sayfa görsellerini üretirken **hem karakter referansını hem o hikayenin kapağını** referans görsel olarak ver (image-to-image / reference özelliği). Böylece ortam, ışık ve karakterler sayfadan sayfaya sabit kalır.
4. Her promptun sonuna şunu ekle: *"Bu görsel, verilen referans görsellerle aynı çizim stilinde, aynı karakterlerle ve aynı mekânda olmalı."*

---

## ORTAK STİL BLOĞU
*(Her promptun başına aynen kopyala)*

> Modern animasyon filmi karesi görünümünde, yüksek detaylı 2D dijital illüstrasyon (Pixar/DreamWorks konsept sanatı estetiği). Hedef kitle 10-12 yaş ortaokul öğrencileri: karakterler sevimli ama bebeksi değil; gerçekçi çocuk oranlarına yakın, ifadeleri zengin ve esprili. Sinematik ışık, yumuşak gölgeler, dokulu boyama. Renk paleti: sıcak amber ve turuncu tonları, zümrüt yeşili vurgular, indigo-lavanta gölgeler. Mekân: Ege kasabası havasında sıcak bir Türk mahallesi — beyaz badanalı iki katlı evler, kiremit çatılar, begonvil sarmaşıkları, arnavut kaldırımı, elektrik direkleri arasında çamaşır ipleri. Eller anatomik olarak doğru ve beş parmaklı; aletler gerçekçi boyutta. Görselde hiçbir yazı/harf/rakam bulunmasın. ⚠️ TEK İSTİSNA — DÜKKÂN TABELALARI: kısa ve doğru Türkçe tabela yazısına (örn. FIRIN, NALBUR, YENİ MARKET, İLAN PANOSU) izin verilir; bunun dışında grafiklerde, defterlerde, fişlerde, afişlerde, konuşma balonlarında, nesnelerin üzerinde HİÇBİR yazı/harf/rakam olamaz. Türkçe karakterleri bozuk çıkan tabela kabul edilmez — emin değilsen tabelayı BOŞ bırak. **Sahnedeki matematiksel öge (çizgi, açı, çember, çokgen...) geometrik olarak DOĞRU ve görselin odak noktası olmalı.** Yatay 16:9 format, yüksek çözünürlük.

## SABİT MEKÂN TANIMLARI
*(Sahnede geçtiğinde aynen kullan)*

- **ARSA/SAHA:** Nalbur dükkânının arkasında geniş, dümdüz, sıkıştırılmış açık kahverengi toprak arsa; kenarlarında gelincikli otlar ve tel örgü; içinde gezinen 5 kahverengi tavuk ve 1 eleştirel bakışlı kızıl horoz. Uzakta alçak yeşil tepeler ve tren hattı silueti. (Konu 1'den sonra: zemine tebeşirle çizilmiş beyaz saha çizgileri ve orta çember de görünür.)
- **NALBUR DÜKKÂNI:** Dede'nin nalburu — cephesi soluk mavi ahşap kepenkli, önünde iç içe geçmiş çinko kovalar, süpürgeler, ip yumakları, ahşap merdivenler; kapı üstünde boş (yazısız) tabela.
- **BALKON:** Mübeccel Teyze'nin ferforje korkuluklu, sardunya saksılı ikinci kat balkonu; korkulukta küçük kilim.
- **MEYDAN:** Mahallenin ortasında, ortasında taş çeşme olan küçük meydan; çeşmenin başında iki tekir kedi; meydana dört sokak açılır.
- **FIRIN (Konu 2):** Meydana bakan taş cepheli fırın; kemerli ahşap kapısı, camekânında ekmekler, bacasından ince duman, önünde uzun ahşap masa ve iki bank.

## KARAKTER KADROSU
*(Promptta geçen karakterin tanımını aynen yapıştır — kıyafet ve renkler asla değişmez)*

- **KAHRAMAN (anlatıcı):** 11 yaşında Türk erkek çocuğu; buğday tenli, iri kahverengi gözlü, dağınık kıvırcık koyu kahverengi saçlı, sol kaşının ucunda minik yara izi. Zümrüt yeşili bisiklet yaka tişört, turuncu kargo şort, mavi-beyaz spor ayakkabı, sol bileğinde örgü bileklik. Kareli kapaklı defteri ve kulağının üstünde sarı kalem.
- **DEDE:** 72 yaşında; kısa boylu, tıknaz, kalın beyaz pos bıyıklı, kırışık güleç yüzlü, kalın gri kaşlı. Gri kasket, açık mavi gömlek (kolları sıvalı), koyu gri yelek, kahverengi kadife pantolon, bej nalbur önlüğü, yeleğinde köstekli saat zinciri.
- **ELİF (kardeş):** 8 yaşında kız; kahramanla aynı ten ve göz rengi, iki yana örülmüş koyu kahverengi saçlar, kırmızı tokalar. Hardal sarısı elbise, beyaz tayt, kırmızı sandalet. Bakışları zeki ve muzip.
- **EMRE:** 10 yaşında; zayıf, kepçe kulaklı, kısa siyah saçlı, önü açık dişli, hep gülen. Kırmızı çizgili beyaz tişört, lacivert şort, yeşil sağlık terliği.
- **AYŞE:** 10 yaşında; koyu tenli, topuz siyah kıvırcık saçlı, yuvarlak gözlüklü. Mor tişört, kot pantolon, pembe spor ayakkabı.
- **MÜBECCEL TEYZE:** 65 yaşında; toplu, pembe yanaklı, çiçekli krem başörtülü, bordo hırka, çiçekli pazen elbise. Boynunda siyah eski model dürbün ASILI durur — dürbünü gözüne GÖTÜRMEZ (yalnızca çok uzaktaki bir şeye bakması özellikle istenirse kullanır). Genelde tek eli balkon korkuluğunda, diğer eliyle işaret eder ya da eli belindedir. Yüz ifadesi hep "ben demiştim".
- **MUHTAR:** 55 yaşında; uzun boylu, ZAYIF, İNCE SİYAH bıyıklı, hafif dazlak. Kendine büyük gri takım elbise, kırmızı kravat. Komik derecede resmi, göğsü kabarık; ellerini arkasında kavuşturur ya da koltuğunun altında resmî evrak dosyası taşır. GÜMÜŞ MEGAFONU YALNIZCA fiilen anons yaptığı sahnelerde elindedir; diğer tüm sahnelerde megafon YOKTUR. (Kasket/yelek/pos bıyık YOK — dede ile karıştırma!)
- **CEMAL USTA (fırıncı, Konu 2):** 50 yaşında; iri yapılı, güleç, kırmızı yanaklı, alnında ter bandanası, beyaz fırıncı önlüğü, kolları unlu. Elinde uzun ekmek küreği.
- **NECMİ (kargocu, Konu 3):** 30 yaşında; sarı-lacivert kargo üniforması, kasket, elinde el terminali ve koli; yüzünde "sisteme küsmüş" yorgun ifade.
- **KADİR USTA (fayansçı, Konu 4):** 60 yaşında; esmer, kısa kır saçlı, çok ciddi bakışlı, az konuşan tip; gri işçi tulumu, dizlik, omzunda şerit metre, yanında kilitli tahta sandık.

### 0) `karakter_referans.png` *(üretim referansı — hikayelerde kullanılmaz)*
> [ORTAK STİL] Karakter tanıtım sayfası (model sheet): nötr açık krem arka plan önünde yan yana, tam boy, kameraya dönük on karakter: KAHRAMAN, DEDE, ELİF, EMRE, AYŞE, MÜBECCEL TEYZE, MUHTAR, CEMAL USTA, NECMİ, KADİR USTA *(tanımları aynen yapıştır)*. Her biri kendine özgü duruşta. Yazı yok.

---

## KONU 1 — "Mahalle Turnuvası ve Kayıp Çizgiler" (`tema1-konu1-kayip-cizgiler/`)
**Sahne sabitleri (her prompta ekle):** Tüm sahneler ARSA/SAHA ve çevresinde geçer. Zaman akışı: sayfa 1 sabah → sayfa 4 alacakaranlık. Matematik odağı: nokta, dümdüz çizgi (doğru parçası), kusursuz çember, dik direk.

*(Bu konunun görselleri üretildi ✅ — yeniden üretim gerekirse önceki sürümdeki promptlar geçerlidir.)*

---

## KONU 2 — "Eşit Dilim Davası" (`tema1-konu2-acilar/`)
**SAHNE SABİTLERİ (her prompta aynen ekle):** Bütün sahneler MEYDAN'da, FIRIN'ın önünde geçer (FIRIN tanımını yapıştır). Fırının önündeki **uzun ahşap masa** her karede aynıdır ve dev yuvarlak börek tepsisi hep bu masanın üstündedir. Zaman akışı: sayfa 1 öğlen parlak güneş → sayfa 4 ikindi/altın saat. Matematik odağı her karede net görünür: **daire biçimli tepsi, dilim açıları, şeffaf yarım ay açıölçer**. Açıölçer HER ZAMAN gerçekçi boyutta (bir el genişliğinde), yarım daire biçimli, ince ölçek çizgili.

### 1) `assets/t1k2_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN tanımı] MEYDAN'da FIRIN önündeki uzun ahşap masada dev, yuvarlak, altın gibi kızarmış börek tepsisi; merkezde ve hafif üstten görünüyor. KAHRAMAN masanın arkasında ayakta; iki eliyle göğüs hizasında gerçekçi boyutta şeffaf açıölçer tutuyor, merakla inceliyor — elinde başka HİÇBİR alet yok (bıçak/kesici KESİNLİKLE YOK). Masanın iki yanında boş tabaklı, sabırsız iki mahalle çocuğu. Arkada FIRIN cephesi ve tüten baca. Alt üçte birlik alan başlık için sade. Kamera: göz hizasına yakın, hafif üstten.

### 2) `assets/t1k2_sayfa1.png` — Dev börek geliyor
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, MUHTAR, CEMAL USTA, MÜBECCEL TEYZE tanımları] Aynı MEYDAN, öğlen güneşi. CEMAL USTA fırının kemerli kapısından iki eliyle dev yuvarlak börek tepsisini çıkarıyor, tepsiden buhar yükseliyor; ahşap masaya doğru yürüyor. Solda MUHTAR megafonuyla anons pozunda. Masanın çevresinde bekleyen kalabalık: KAHRAMAN önde defteri koltuğunda kaygılı, EMRE ve AYŞE tabaklarıyla zıplıyor. Meydanın kenarındaki BALKON'da MÜBECCEL TEYZE, dürbünü boynunda asılı, bir eliyle tepsiyi işaret edip konuşuyor. Kamera: meydanı gösteren geniş plan, fırın cephesi arka fonda.

### 3) `assets/t1k2_sayfa2.png` — Göz kararı faciası
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, EMRE tanımları] Aynı ahşap masa, aynı meydan; kamera masaya yakın, 45 derece üstten — tepsi görselin odağı ve dilimler NET görünüyor. Börek, merkezden çıkan ÇARPIK çizgilerle 6-7 FECİ DERECEDE EŞİTSİZ dilime bölünmüş. Bu eşitsizlik görselin ana esprisi ve ABARTILI olmalı: bir dilim kürdan gibi İNCECİK (yaklaşık 10 derecelik kıl gibi bir kama), hemen yanındaki dilim ise tepsinin NEREDEYSE ÇEYREĞİNİ kaplayan devasa bir parça; diğer dilimler de irili ufaklı, çizgiler eğri büğrü. DİKKAT: dilimler kesinlikle eşit veya düzenli GÖRÜNMEMELİ — simetri YOK, düzgün pasta dilimi YOK. EMRE kürdan gibi incecik dilimi iki parmağıyla havaya kaldırmış kahkaha atıyor; dilimin komik inceliği elinde net görünüyor. KAHRAMAN masa başında elleri iki yanında, mahcup (elinde alet yok). DEDE yanında kasketini kaldırmış, bir eliyle havada daire çizer jesti yapıyor. Arka fonda fırın kapısı.

### 4) `assets/t1k2_sayfa3.png` — Açıölçer adaleti
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, EMRE tanımları] Aynı masa, ikindi ışığı; kamera masa hizasından yakın plan. Börek tepsisi bu kez SEKİZ KUSURSUZ EŞİT dilime ayrılmış — dilim çizgileri merkezden geçen düzgün ışınlar gibi, her dilim açısı eşit (45°'lik dilimler görsel olarak doğru). Tepsinin üzerine, merkez hizasına yerleştirilmiş şeffaf plastik AÇIÖLÇER: klasik okul açıölçeri gibi YARIM AY / YARIM DAİRE biçiminde (D harfi formu), düz alt kenarlı, kavisli üst kenarında ince ölçek çizgileri — TAM DAİRE DEĞİL, kesinlikle yarım daire; boyutu bir el genişliğinde. KAHRAMAN tek eliyle ahşap saplı yuvarlak hamur ruletini son çizgide kaydırıyor, dili yandan çıkmış. ELİF açıölçerin düz kenarının orta noktasını (merkez işaretini) işaret ediyor. Arkada EMRE iki eş dilimi üst üste koymuş, fark bulamayınca şaşkın. Arka fonda fırın cephesi.

### 5) `assets/t1k2_sayfa4.png` — Mahallede açı avı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, MÜBECCEL TEYZE tanımları] Aynı meydan, altın saat ışığı; kamera fırının önünden sokağa bakıyor. Tek karede net üç açı örneği: (1) fırının ARALIK duran kemerli kapısı — kapı ile kasa arasında dar açı belirgin; (2) fırın duvarına yaslanmış ahşap merdiven — merdivenle zemin arasındaki geniş açı belirgin; (3) iki bina arasındaki çamaşır ipi — direkle yaptığı açı. KAHRAMAN elinde açıölçerle çamaşır ipinin açısını ölçüyor, ELİF deftere not alıyor. BALKON'da MÜBECCEL TEYZE kayan mandalları gösteriyor. Açılar abartılı ve geometrik olarak doğru.

---

## KONU 3 — "Sokağın İki Adı" (`tema1-konu3-dogrular/`)
**SAHNE SABİTLERİ (her prompta aynen ekle):** Hikaye mahallenin sokaklarında ve MEYDAN'da geçer (MEYDAN tanımını yapıştır). Kriz sokağı: iki ucunda birer ahşap direk, direklerde biri YEŞİL biri MAVİ iki boş tabela — her karede aynı sokak, aynı tabelalar. Matematik odağı: **uzun düz sokak çizgileri; paralellik, kesişme ve çakışma göze ilk çarpan şey olmalı.** Sokaklar gerçekten dümdüz, paraleller gerçekten paralel çizilmeli.

### 1) `assets/t1k3_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, NECMİ tanımları] Kriz sokağının başı: aynı karede İKİ direk ve İKİ farklı renkte boş tabela (yeşil + mavi) net görünüyor; sokak dümdüz uzayıp gidiyor, perspektifle ufka daralıyor. Sokağın ortasında KAHRAMAN kollarını iki yana açmış "hangisi?" der gibi izleyiciye bakıyor. Yanında NECMİ koli ve el terminaliyle umutsuz. İki yanda begonvilli beyaz evler. Alt üçte birlik alan başlık için sade. Kamera: sokağın ortasından, tek nokta perspektifi (düz çizgiler vurgusu).

### 2) `assets/t1k3_sayfa1.png` — Tabela krizi
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, MUHTAR, NECMİ, MÜBECCEL TEYZE tanımları] Aynı kriz sokağı, sabah ışığı, aynı tek nokta perspektifi: önde yeşil tabelalı direk, sokağın öbür ucunda mavi tabelalı direk — ikisi de aynı düz sokağın üstünde olduğu net görülüyor. Sokağın ortasında NECMİ kolisiyle kalakalmış, bir o tabelaya bir bu tabelaya bakıyor, başının üstünde karışıklık çizgileri. MUHTAR telaşla koşarak geliyor. KAHRAMAN kenarda defterine not alıyor. Yol üstündeki BALKON'da MÜBECCEL TEYZE, dürbünü boynunda, iki eli korkulukta, olayı yukarıdan süzüyor.

### 3) `assets/t1k3_sayfa2.png` — Harita masası
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, DEDE tanımları + NALBUR DÜKKÂNI tanımı] NALBUR DÜKKÂNI içi, tezgâha serilmiş büyük beyaz kâğıt — kâğıttaki çizim görselin odağı: kalın siyah çizgilerle mahalle planı; üstte YAN YANA, HİÇ KESİŞMEYEN iki uzun paralel çizgi (araları her yerde eşit), altta BİR NOKTADA KESİŞEN iki çizgi (kesişim noktası kırmızı işaretli). Kâğıtta SADECE ÇİZGİLER var — ÜZERİNDE HİÇBİR YAZI, HARF, ETİKET, KELİME YOK; görselin hiçbir yerinde yazı yok. ELİF cetvelle çizgi çekiyor, KAHRAMAN kulağından aldığı sarı kalemle not alıyor, DEDE parmağıyla paralel çizgileri gösteriyor. Raflarda kovalar, ipler. Kamera: masaya 45 derece üstten, harita net okunur.

### 4) `assets/t1k3_sayfa3.png` — Kavşakta açı dersi
> ⚠️ DİKKAT: Bu sahne AÇIK HAVADA, meydanda geçer — dükkân içi, masa veya kâğıt YOK! Referans olarak masa sahnesini DEĞİL, kapak/sayfa1 sokak görsellerini kullan.
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, DEDE tanımları] Gündüz, MEYDAN'daki taş çeşmenin önü, arnavut kaldırımlı açık alan; ZEMİNE tebeşirle çizilmiş İKİ KESİŞEN DEV DOĞRU görselin odağı — kesişim noktasında dört açı, karşılıklı iki açı yayı yeşil tebeşirle (ters açılar eş!), diğer ikisi turuncu tebeşirle işaretli; çizgiler dümdüz ve geometrik olarak doğru. Zeminde ve görselde HİÇBİR YAZI/HARF YOK, sadece çizgi ve yaylar. KAHRAMAN yere diz çökmüş bir yeşil açıyı açıölçerle ölçüyor; ELİF çaprazdaki eş yeşil açıyı işaret ediyor. DEDE çeşmenin kenarında izliyor. Çeşmenin iki yanında karşılıklı, aynı pozda oturan iki tekir kedi. Arka planda beyaz badanalı evler. Kamera: hafif kuş bakışı — zemindeki tebeşir çizgileri tam görünsün.

### 5) `assets/t1k3_sayfa4.png` — Çakışık gerçeği
> ⚠️ DİKKAT: Bu sahne AÇIK HAVADA, sokakta geçer — dükkân içi veya masa YOK! Referans olarak masa sahnesini DEĞİL, kapak/sayfa1 sokak görsellerini kullan.
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, MUHTAR, NECMİ tanımları] Kriz sokağı, gün batımı ışığı (turuncu-mor gökyüzü). KAHRAMAN sokağın ortasında ayakta, iki eliyle açtığı büyük kâğıt haritayı MUHTAR'a gösteriyor; haritada görselin odağı: TEK bir düz çizginin üstünde üst üste binmiş kırmızı ve mavi KESİK çizgiler (çakışık iki doğru = tek sokak) — haritada BAŞKA HİÇBİR ŞEY ve HİÇBİR YAZI YOK. MUHTAR elleri dizlerinde, haritaya eğilmiş, kaşları havada "vay" ifadesi (megafon YOK). Arkada NECMİ aynı sokaktaki bir kapıya kolisini huzurla teslim ediyor; sokağın iki ucundaki YEŞİL ve MAVİ boş tabelalar görünüyor. Görselde hiçbir yazı yok. Kamera: göz hizası, sokak perspektifi.

---

## KONU 4 — "Altıgen Peşinde" (`tema1-konu4-cokgenler/`)
**SAHNE SABİTLERİ (her prompta aynen ekle):** Hikaye NALBUR DÜKKÂNI önünde ve MEYDAN'da geçer (tanımları yapıştır). KADİR USTA'nın kilitli tahta sandığı ve rengârenk fayanslar her karede aynıdır: kırmızı üçgen, mavi kare, sarı beşgen, yeşil altıgen, mor sekizgen, pembe yuvarlak. Matematik odağı: **fayans şekilleri geometrik olarak kusursuz** (altıgen 6 eşit kenarlı, beşgen 5 eşit kenarlı...) ve her karede ön planda.

### 1) `assets/t1k4_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, KADİR USTA tanımları + NALBUR DÜKKÂNI tanımı] NALBUR DÜKKÂNI önü; açık tahta sandıktan etrafa saçılmış fayans seti (kırmızı üçgen, mavi kare, sarı beşgen, yeşil altıgen, mor sekizgen, pembe yuvarlak — hepsi kusursuz geometrik biçimde). KAHRAMAN sandığın başına çömelmiş, yeşil ALTIGEN fayansı iki eliyle ışığa tutmuş inceliyor. Arkasında KADİR USTA kollarını kavuşturmuş ciddi ama onaylayan. Zeminde çamur birikintileri, camda DEDE'nin silüeti. Alt üçte birlik alan başlık için sade. Kamera: hafif alçak açı.

### 2) `assets/t1k4_sayfa1.png` — Çamur krizi ve ustanın gelişi
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, KADİR USTA, MÜBECCEL TEYZE tanımları + NALBUR DÜKKÂNI, BALKON tanımları] Yağmur sonrası aynı dükkân önü: zemin parlak çamur deryası, kapı eşiğinde dizili çamurlu ayakkabılar, DEDE eşikte umutsuz. Arnavut kaldırımlı sokaktan KADİR USTA geliyor: omzunda metre, elinde tahta sandık, arkasında fayans kolili el arabası. KAHRAMAN taşların üstünde seke seke ilerliyor. BALKON'da MÜBECCEL TEYZE çamuru işaret ediyor. Bulutları yeni açan gökyüzü, ıslak yüzey yansımaları. Kamera: geniş plan.

### 3) `assets/t1k4_sayfa2.png` — Sandıktaki şekiller
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, EMRE, KADİR USTA tanımları] Aynı dükkân önü, kurumuş bir köşe; açık sandığın çevresine düzenle dizilmiş fayans seti görselin odağı — her şekil net ve kusursuz: kırmızı üçgen, mavi kare, sarı beşgen, yeşil altıgen, mor sekizgen. ELİF pembe YUVARLAK fayansı kaldırmış soru soruyor; EMRE köşesi kırık, KAPANMAMIŞ bir fayans parçasını gösteriyor (açık şekil net görünsün). KADİR USTA altıgeni işaret ediyor. KAHRAMAN şekilleri defterine çiziyor. Kamera: halka olmuş grubu 45 derece üstten.

### 4) `assets/t1k4_sayfa3.png` — Köşegen numarası
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, DEDE tanımları] Aynı dükkân önündeki tezgâh, akşam ışığı; kamera tezgâh hizasından yakın plan. Görselin odağı: büyük SARI BEŞGEN fayans üzerine DEDE'nin tebeşirle çizdiği köşegenler — köşeden karşı köşeye beş düz çizgi, içerde yıldız deseni oluşmuş (geometrik olarak doğru). ELİF elinde küçük kırmızı ÜÇGEN fayansla şaşkın; çizecek köşegen bulamıyor. KAHRAMAN eğilmiş hayranlıkla izliyor. Kenarda diğer fayanslar dizili.

### 5) `assets/t1k4_sayfa4.png` — Altıgen meydan ve arı peteği
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, KADİR USTA tanımları + MEYDAN tanımı] MEYDAN, güneşli gün; kamera hafif kuş bakışı. Görselin odağı iki zemin deseni kontrastı: solda KADİR USTA'nın diz çöküp döşediği YEŞİL ALTIGEN fayanslar — kusursuz bal peteği düzeni, SIFIR boşluk; sağda yarım bırakılmış SARI BEŞGEN denemesi — beşgenlerin arasında belirgin üçgen boşluklar. ELİF havada uçan üç arıyı ve köşedeki gerçek petek parçasını gösteriyor; petek deseni fayans deseniyle birebir aynı görünüyor. KAHRAMAN iki deseni karşılaştırıp defterine bakıyor. Çeşme arka planda.

---

## KONU 5 — "Üç Köşeli Zafer" (`tema1-konu5-ucgenler/`)
**SAHNE SABİTLERİ (her prompta aynen ekle):** Hikaye ARSA/SAHA'da (artık beyaz çizgili, orta çemberli futbol sahası — Konu 1'de çizildi) ve NALBUR DÜKKÂNI tezgâhında geçer. Flamalar: ipe dizilmiş rengârenk KARTON ÜÇGEN bayraklar — her karede aynı renk seti (kırmızı, sarı, yeşil, mavi, mor). Matematik odağı: **üçgen biçimleri geometrik olarak doğru** — eşkenar gerçekten eşkenar, dik üçgenin dik açısı net, geniş açılı belirgin yayvan.

### 1) `assets/t1k5_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN tanımı + ARSA/SAHA tanımı] Final günü SAHA: beyaz tebeşir çizgileri ve orta çember net görünüyor; sahanın üzerinde iplere dizilmiş rengârenk üçgen flamalar dalgalanıyor. Önde KAHRAMAN, bir elinde gerçekçi boyutta metal pergel, diğer elinde kusursuz EŞKENAR üçgen karton flama, gururlu gülümseme. Arkada kale, toplanan kalabalık silueti, tel örgü ve tepeler. Altın saat ışığı, bayram havası. Alt üçte birlik alan başlık için sade. Kamera: hafif alçak açı.

### 2) `assets/t1k5_sayfa1.png` — Flama faciası
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, MÜBECCEL TEYZE tanımları + BALKON tanımı] Dükkân yanındaki avlu, sabah; yere serilmiş karton flama yığını görselin odağı: hepsi üçgen ama komik derecede birbirinden farklı — aşırı sivri uzun bir tane, yamyassı geniş açılı bir tane, kocaman ve minicik olanlar (farklar abartılı ve net). KAHRAMAN ve ELİF ortada makaslarla oturuyor, çevrede karton kırpıntıları, yüzlerde "bu iş büyüdü" ifadesi. BALKON'dan MÜBECCEL TEYZE, dürbünü boynunda asılı, eliyle yassı flamayı gösterip burun kıvırıyor. Kamera: yığını gösteren 45 derece üstten.

### 3) `assets/t1k5_sayfa2.png` — Dede flamaları ayırıyor
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, EMRE tanımları + NALBUR DÜKKÂNI tanımı] Dükkân tezgâhı; görselin odağı tezgâhtaki ÜÇ AYRI KÜME: solda eşkenar üçgen flamalar (üç kenar eşit, düzgün), ortada uzun ikizkenar flamalar (iki kenar eşit), sağda her kenarı farklı çeşitkenar flamalar — kümeler arası fark bir bakışta anlaşılır. DEDE bir flamanın kenarını iple ölçüyor. KAHRAMAN gönyeyi başka bir flamanın köşesine dayamış dik açı arıyor (gönye gerçekçi boyutta). EMRE yassı flamayı başının üstünde tutmuş şaklabanlık yapıyor. Sıcak dükkân ışığı. Kamera: tezgâh hizası.

### 4) `assets/t1k5_sayfa3.png` — 180 derece numarası
> [ORTAK STİL + SAHNE SABİTLERİ + ELİF, KAHRAMAN tanımları] Tezgâh üstü çok yakın plan, lamba ışığı. Görselin odağı: yırtılmış karton üçgenin ÜÇ KÖŞE PARÇASI masada yan yana dizilmiş; üç açı tam birleşerek dümdüz bir doğru boyunca yarım daire (180°) oluşturuyor — düz kenarları aynı çizgide, geometrik olarak doğru. Yanında yırtılmadan önceki hâlini gösteren sağlam bir eş üçgen duruyor. ELİF muzip gülümsüyor; KAHRAMAN masaya eğilmiş, gözleri faltaşı. Kenarda yırtılmayı bekleyen flamalar.

### 5) `assets/t1k5_sayfa4.png` — Pergelle inşa ve final
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE tanımları + ARSA/SAHA tanımı] İki katmanlı sahne, alacakaranlık. Önde tezgâh üstünde büyük beyaz karton — görselin odağı: çizili bir yatay doğru parçası, iki ucundan çizilmiş ve birbirini kesen İKİ TEBEŞİR ÇEMBERİ, üstteki kesişim noktasından tamamlanmış kusursuz üçgen (inşa geometrik olarak doğru). KAHRAMAN gerçekçi boyutta pergelle ikinci çemberi tamamlıyor; DEDE onaylayarak eğilmiş. Arka planda ışıklandırılmış SAHA: iplerde birbirinin tıpatıp eşi eşkenar flamalar, koşan çocuk siluetleri, şenlik ışıkları. Kamera: kartondan sahaya derinlik veren plan.

---

## 2. TEMA / KONU 1 — Çok Basamaklı Doğal Sayılar
### Hikaye: "Gökyüzü Gecesi ve Kayıp Sıfırlar" (`tema2-konu1-buyuk-sayilar/`)

**Yeni karakter:**
- **GÖKÇE ABLA (gökbilimci):** 28 yaşında kadın; uzun siyah saçları atkuyruklu, sempatik ve enerjik; lacivert üzerine yıldız desenli hırka, kot pantolon, beyaz spor ayakkabı, boynunda kimlik kartı askısı. Yanında büyük beyaz bir teleskop.

**SAHNE SABİTLERİ (her prompta aynen ekle):** Hikaye MEYDAN'da geçer (MEYDAN tanımını yapıştır). Meydanın ortasında üç ayaklı, büyük BEYAZ TELESKOP ve yanında ahşap bir sehpa üzerinde gezegen kartları destesi — kartlar lacivert zeminli, üzerlerinde birer gezegen resmi (yazı/rakam GÖRÜNMEZ, sadece soyut çizgiler). Zaman akışı: sayfa 1-3 gündüz/ikindi → sayfa 4 yıldızlı gece. Matematik odağı: uzun kartlar, üçerli gruplara ayırma jestleri, basamak tablosu.

### 1) `assets/t2k1_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN tanımı] Yıldızlarla dolu lacivert gece gökyüzü altında MEYDAN; ortada büyük beyaz teleskop hafif yukarı dönük. Önünde KAHRAMAN, iki eliyle kendi boyuna yakın UZUN bir gezegen kartını tutuyor (kartta bir gezegen resmi ve rakam yerine geçen soyut uzun çizgi dizisi), yüzünde "bunu nasıl okuyacağım?" paniği. Gökyüzünde parlak Satürn ve yıldızlar. Alt üçte birlik alan başlık için sade. Kamera: hafif alçak açı, teleskop ve kart net.

### 2) `assets/t2k1_sayfa1.png` — Teleskop mahalleye geliyor
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, MUHTAR, GÖKÇE ABLA, MÜBECCEL TEYZE tanımları + BALKON tanımı] Gündüz, MEYDAN. GÖKÇE ABLA meydanın ortasına büyük beyaz teleskopu kuruyor; yanındaki ahşap sehpada gezegen kartları destesi. Solda MUHTAR megafonuyla anons yapıyor. Çocuk kalabalığı hayranlıkla teleskopa bakıyor: KAHRAMAN önde, defteri koltuğunda; EMRE teleskopun borusuna gözünü dayamaya çalışıyor. BALKON'da MÜBECCEL TEYZE, boynundaki kendi dürbününü eliyle tutup teleskopla kıskançlıkla karşılaştırıyor. Kamera: geniş plan.

### 3) `assets/t2k1_sayfa2.png` — Dedenin bölük dersi
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, EMRE tanımları] İkindi, MEYDAN'daki ahşap sehpanın başı; kamera sehpaya yakın. Görselin odağı: DEDE'nin elindeki uzun gezegen kartı — kart üzerindeki uzun soyut işaret dizisini kaleminden çıkan İKİ DİKEY ÇİZGİYLE ÜÇERLİ GRUPLARA ayırmış (üç grup net görünüyor; rakam yok, soyut kutucuklar var). DEDE kasketini kaldırmış, asker anlatır gibi bir eli havada. KAHRAMAN aydınlanmış ifadeyle karta bakıyor. EMRE arkada parmaklarıyla saymaya çalışıyor, kafası karışık. Kamera: sehpa hizası.

### 4) `assets/t2k1_sayfa3.png` — Elif'in basamak tablosu
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF tanımları] İkindi, sehpanın üstüne serilmiş büyük beyaz kâğıt — görselin odağı: ELİF'in çizdiği renkli BASAMAK TABLOSU: yan yana 8-9 boş kutudan oluşan tablo, kutular sağdan sola üçerli gruplar hâlinde üç farklı renkle (yeşil-mavi-turuncu) boyanmış; üstlerinde küçük soyut başlık şeritleri (yazı yok). ELİF elinde iki kalemle, biri sağdaki yeşil kutuyu biri soldaki turuncu kutuyu gösteriyor — "aynı rakam, farklı koltuk" jesti. KAHRAMAN iki eliyle kafasını tutmuş, "vay be" ifadesi. Kamera: 45 derece üstten, tablo net.

### 5) `assets/t2k1_sayfa4.png` — Gökyüzü gecesi
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, GÖKÇE ABLA, ELİF, MÜBECCEL TEYZE tanımları + BALKON tanımı] Yıldızlarla dolu gece, MEYDAN kalabalık; sıcak fener ışıkları. Ortada KAHRAMAN küçük bir platformda, elinde mikrofon ve gezegen kartı, kendinden emin sunum yapıyor. GÖKÇE ABLA teleskopun başında; teleskopa gözünü dayamış sıradaki çocuk ELİF. Gökyüzünde halkalarıyla parlak Satürn ve samanyolu. BALKON'da MÜBECCEL TEYZE — bu sefer İSTİSNA olarak — dürbünüyle GÖKYÜZÜNE bakıyor (uzağa bakıyor, tutarlı!). Kamera: kalabalığın arkasından sahneye ve gökyüzüne bakan geniş sinematik plan.

---

## 2. TEMA / KONU 2 — Gerçek Yaşam Problemleri
### Hikaye: "Kermes Hesabı" (`tema2-konu2-problemler/`)

**SAHNE SABİTLERİ (her prompta aynen ekle):** Hikaye MEYDAN'da geçer (MEYDAN tanımını yapıştır). Kermes düzeni her karede aynıdır: meydana dizilmiş, üstleri kırmızı-beyaz kareli örtülü AHŞAP TEZGAHLAR — solda gözleme tezgâhı (saç ocağı), ortada limonata standı (büyük cam sürahiler, limonlar), sağda kitap ayracı ve oyuncak tezgâhı; en önde KASA MASASI: küçük ahşap masa, üstünde metal para kutusu ve kareli defter. İplerde renkli üçgen flamalar (Konu 5'ten kalma!). Matematik odağı: para sayma, defterdeki hesaplar, parmakla sayma jestleri. Görsellerde HİÇBİR YAZI/RAKAM yok — fiyat etiketleri boş renkli kartlar olarak çizilir.

### 1) `assets/t2k2_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN tanımı] Şenlikli kermes MEYDANI; önde KASA MASASI'nda oturan KAHRAMAN: bir elinde kalem, önünde açık kareli defter ve metal para kutusu; banknot ve madeni para destelerini ciddi bir ifadeyle sayıyor, kulağının üstünde sarı kalemi. Arkasında bulanık kalabalık, kareli örtülü tezgahlar ve renkli flamalar. Altın saat ışığı. Alt üçte birlik alan başlık için sade. Kamera: kasa masasına hafif üstten.

### 2) `assets/t2k2_sayfa1.png` — Kermes hazırlığı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, MUHTAR, MÜBECCEL TEYZE, DEDE, ELİF tanımları + BALKON tanımı] Sabah, MEYDAN'da kurulum telaşı: DEDE limonata standına büyük cam sürahileri diziyor; ELİF tezgâha rengarenk kitap ayraçları seriyor; EMRE ve AYŞE kutulardan oyuncak çıkarıyor. BALKON'da MÜBECCEL TEYZE elinde oklava, önünde hamur teknesi, aşağıya seslenerek talimat veriyor. MUHTAR koltuğunun altında evrak dosyası, ortada denetim yaparak dolanıyor (megafon YOK). KAHRAMAN kasa masasını taşıyor, yüzünde "yedinci görev" yorgunluğu. Kamera: geniş plan, kurulum kaosu sevimli.

### 3) `assets/t2k2_sayfa2.png` — Dedenin limon hesabı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, EMRE, ELİF tanımları] Limonata standı başı, öğlen ışığı. DEDE bir elinde limon, diğer eliyle havada hesap yapar gibi parmak sayıyor; önünde üç tahta kasa dolusu parlak sarı limon. EMRE ağzı açık, hayran, kafasının üstünde karışık düğüm çizgileri çözülüp düzleşiyor (anlama anı). Kenarda ELİF, EMRE'ye parmaklarıyla "on ile çarpma" jesti yapıyor. KAHRAMAN deftere not alıyor. Kamera: stand hizası, limon kasaları net.

### 4) `assets/t2k2_sayfa3.png` — Problem merdiveni
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF tanımları] Kasa masasının başı; görselin odağı: ELİF'in kasa masasının yanına dayadığı büyük karton pano — panoda BEŞ BASAMAKLI bir merdiven çizimi, her basamak farklı renkte (yeşil→mavi→sarı→turuncu→kırmızı), basamakların üstünde yazı YOK sadece küçük simgeler: göz (anla), harita (planla), terazi (tahmin), çark (çöz), onay işareti (kontrol). ELİF merdivenin basamaklarını işaret ediyor, öğretmen edasında. KAHRAMAN kasada oturmuş, aydınlanmış ifadeyle panoya bakıyor. Kamera: masa hizası.

### 5) `assets/t2k2_sayfa4.png` — Kermes günü kasa başında
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, MÜBECCEL TEYZE, DEDE, CEMAL USTA tanımları] İkindi, kermes en civcivli hâlinde: kalabalık tezgahların önünde kuyrukta. Solda MÜBECCEL TEYZE saç ocağında gözleme çeviriyor (bu kez balkonda DEĞİL, tezgâhta!). DEDE limonata dolduruyor. CEMAL USTA elinde üç gözlemeyle kasaya doğru geliyor. Merkezde KAHRAMAN kasa masasında: bir eliyle para üstü uzatıyor, diğer eliyle defter tutuyor, kendinden emin gülümsüyor. Renkli flamalar rüzgârda. Kamera: kasa merkezli geniş şenlik planı.

---

## 3. TEMA — Dikdörtgende Çevre ve Alan
### Hikaye: "Yirmi Dört Metre Çit" (`tema3-cevre-alan/`)

**SAHNE SABİTLERİ (her prompta aynen ekle):** Hikaye, ARSA/SAHA'nın (tanımı yapıştır) yanındaki boş köşede geçer: futbol sahasının beyaz çizgileri arka planda görünür. Bahçe malzemeleri her karede aynıdır: gümüş renkli TEL ÇİT rulosu, ahşap kazıklar, tahta kasalarda yeşil DOMATES FİDELERİ. Matematik odağı: çitin dikdörtgen sınırı ve toprağa dizilen KARE KARTONLAR (birim kareler) — dikdörtgenler geometrik olarak doğru, birim kartonlar eşit boyutlu ve boşluksuz dizilmiş.

### 1) `assets/t3k1_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN tanımı] Güneşli sabah, saha kenarındaki boş toprak köşe. KAHRAMAN önde: bir omzunda gümüş tel çit rulosu, diğer elinde ahşap kazık, ayağının dibinde domates fidesi kasası; yüzünde "planlıyorum" ifadesiyle toprağa bakıyor. Toprakta tebeşirle çizilmiş İKİ plan taslağı: biri upuzun ince dikdörtgen, biri geniş kare (kontrast net). Arka planda sahanın beyaz çizgileri ve tel örgü. Alt üçte birlik alan başlık için sade. Kamera: hafif alçak açı.

### 2) `assets/t3k1_sayfa1.png` — Kamyon ve fideler
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, MUHTAR, DEDE, MÜBECCEL TEYZE tanımları + BALKON tanımı] Sabah; saha kenarına yanaşmış küçük açık kasa kamyon: kasasından tel çit rulosu, kazıklar ve fide kasaları indiriliyor. DEDE teli eliyle yoklayarak inceliyor. MUHTAR kamyon şoförüne teslim evrakı imzalatıyor (megafon YOK). KAHRAMAN kollarını kavuşturmuş, ciddiyetle planlıyor; ELİF ve EMRE fide kasalarına bakıyor. BALKON'da MÜBECCEL TEYZE eliyle "bir sıra maydanoz" der gibi işaret parmağını sallıyor. Kamera: geniş plan.

### 3) `assets/t3k1_sayfa2.png` — Koridor bahçe faciası
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, ELİF tanımları] Öğlen; görselin odağı: toprakta kurulmuş UPUZUN ve İNCECİK dikdörtgen çit (bir koridor gibi abartılı dar ve uzun — genişliği bir adım, uzunluğu on adım). Çitin içinde tek sıra hâlinde komik biçimde yürüyen KARINCALAR. KAHRAMAN başında elleri belinde, gururlu ama şüpheye düşmüş. DEDE kasketini kaldırmış, kaşları havada, dudağında alaycı gülümseme. ELİF kenarda parmaklarıyla farklı dikdörtgen boyları sayıyor. Arka planda saha çizgileri. Kamera: koridorun uzunluğunu vurgulayan çapraz açı.

### 4) `assets/t3k1_sayfa3.png` — Birim kare keşfi
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, EMRE tanımları] İkindi; görselin odağı iki bahçenin kontrastı: solda dar koridor bahçe içinde TEK SIRA hâlinde 11 eş kare karton; sağda geniş KARE bahçe içinde 6×6 düzeninde dizilmiş çok sayıda eş kare karton — boşluksuz, ızgara gibi düzgün. ELİF kare bahçenin ortasında kollarını açmış zafer pozunda. EMRE kartonları parmağıyla sayıyor, gözleri faltaşı. KAHRAMAN iki bahçeye dönüşümlü bakıyor, aydınlanma anında. Kamera: iki bahçeyi birden gösteren hafif kuş bakışı.

### 5) `assets/t3k1_sayfa4.png` — Bahçe tamam, dönem finali
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, MUHTAR, MÜBECCEL TEYZE, ELİF, EMRE tanımları] Gün batımı, altın ışık. Tamamlanmış KARE bahçe: gergin tel çit, içeride düzenli sıralarla dikilmiş domates fideleri, bir kenarda ayrı bir maydanoz sırası. Mahalle bahçenin etrafında toplanmış: DEDE elini KAHRAMAN'ın omzuna koymuş, gururlu; MUHTAR elinde resmî kâğıtla geliyor; MÜBECCEL TEYZE (bahçe başında, balkonda değil) maydanoz sırasını onaylayarak inceliyor; ELİF ve EMRE sulama kabıyla fidelere su veriyor. Arka planda saha ve iplerde hâlâ asılı üçgen flamalar. Sıcak, dönem sonu hissi veren veda karesi. Kamera: geniş sinematik plan.

---

# 📗 2. DÖNEM

## 4. TEMA / KONU 1 — Kesirleri Farklı Biçimlerde Temsil Etme
### Hikaye: "Sayıların Üç Dili" (`tema4-konu1-kesir-temsil/`)

**SAHNE SABİTLERİ (her prompta aynen ekle):** Sayfa 1 tren hattı yanındaki çiçekli ÇAYIR'da piknik; sayfa 2-4 NALBUR DÜKKÂNI içinde ve önünde geçer (tanımı yapıştır). Dükkân içi sabittir: ahşap tezgâh, üzerinde eski model gümüş yazar kasa ve bozuk para gözü, raflarda kovalar/fırçalar/mandal kolileri. Matematik odağı: yarım ekmekler, bozuk paralar (madenî kuruşlar), fiyat etiketleri (üzerinde yazı/rakam YOK — boş renkli kartlar) ve camdaki büyük indirim tabelası (boş turuncu tabela). Görsellerde hiçbir yazı/rakam yok.

### 1) `assets/t4k1_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN tanımı + NALBUR DÜKKÂNI tanımı] Dükkânın önü; camda kocaman boş TURUNCU indirim tabelası asılı. KAHRAMAN önde, bir elinde etiket tabancası/boş etiket destesi, diğer elinde havaya kaldırdığı büyük madenî para; yüzünde "bu üçü aynı şey mi?" şaşkın-meraklı ifade. Önündeki tezgâhta üç eş kova yan yana, her birinin üstünde farklı renkte boş etiket kartı (yeşil, mavi, turuncu — üç dil hissi). Alt üçte birlik alan başlık için sade. Kamera: hafif alçak açı.

### 2) `assets/t4k1_sayfa1.png` — Çayırda piknik
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, ELİF, EMRE, AYŞE, MÜBECCEL TEYZE tanımları] Tren hattı yanındaki gelincikli ÇAYIR, öğlen güneşi; yere serilmiş büyük kareli piknik örtüsü. Örtünün ortasında ekmek sepeti: İKİYE BÖLÜNMÜŞ yarım ekmekler net görünüyor (kesir odağı). KAHRAMAN elinde yarım ekmek, parmaklarıyla sayıyor, kafasında hesap. DEDE mangal başında köfte çeviriyor. MÜBECCEL TEYZE (balkonsuz, piknikte!) termosdan çay dolduruyor. ELİF ve AYŞE gülüşüyor, EMRE ağzında kocaman köfte ekmek. Arkada tren geçiyor. Kamera: örtüyü gösteren 45 derece üstten.

### 3) `assets/t4k1_sayfa2.png` — Kuruş dersi
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, EMRE tanımları + NALBUR DÜKKÂNI tanımı] Dükkân içi, tezgâhın başı; görselin odağı: tezgâhın üstüne düzenli sıralar hâlinde dizilmiş MADENÎ PARALAR — büyükten küçüğe kuleler ve yanlarına konmuş İKİYE/DÖRDE bölünmüş daire diyagramları çizili küçük kartlar (yazı yok, sadece bölmeli daireler). ELİF parmağıyla yarıya bölünmüş daire kartını gösteriyor, ders veriyor. KAHRAMAN kuruş kulesini dizerken dinliyor. EMRE kendi cebini ters çevirmiş, cebinden delik görünüyor, komik mahcup ifade. Sıcak dükkân ışığı. Kamera: tezgâh hizası.

### 4) `assets/t4k1_sayfa3.png` — Etiket ve virgül
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE tanımları + NALBUR DÜKKÂNI tanımı] Dükkân içi; KAHRAMAN tezgâhta oturmuş, elinde kalem, önünde etiket destesi; bir kovaya KOCAMAN, kovanın yarısını kaplayan gülünç derecede büyük boş etiket yapıştırılmış (uzun yazı esprisi — yazı görünmez, sadece karalama çizgileri). DEDE yanında, elinde küçük şık bir etiket tutuyor, "böyle olacak" jesti. Raflarda sıra sıra küçük düzgün etiketli ürünler. Kamera: tezgâha yakın plan, iki etiketin boyut kontrastı net.

### 5) `assets/t4k1_sayfa4.png` — İndirim fırtınası
> ⚠️ DİKKAT: Sahne TAMAMEN DIŞ MEKÂNDA geçer — kamera SOKAKTAN dükkânın cephesine bakar. İç mekân öğesi (raf, tezgâh, kasa, iç duvar) görünmez; dükkânın içi yalnızca vitrin camının arkasında hafif bulanık görünebilir. Tek ve net bir mekân: arnavut kaldırımlı sokak + dükkân cephesi.
> [ORTAK STİL + KAHRAMAN, DEDE, MÜBECCEL TEYZE, EMRE tanımları + NALBUR DÜKKÂNI tanımı] İkindi güneşi. Kompozisyon sade ve okunur: Merkezde NALBUR DÜKKÂNI'nın soluk mavi kepenkli cephesi ve kapısı; vitrin camına asılmış BÜYÜK, BOŞ TURUNCU indirim tabelası görselin odağı. Kapının önünde (dışarıda, eşikte) DEDE memnun, kasketini hafif kaldırmış. Sokakta, dükkânın önünde: KAHRAMAN defteri koltuğunda, üç parmağını havaya kaldırmış EMRE'ye anlatıyor; EMRE aydınlanmış. Sağdan MÜBECCEL TEYZE koltuğunda mandal kolisiyle kapıya yürüyor. Arkada sokakta kova taşıyan İKİ komşu silueti (kalabalık az, sahne sade). Kamera: sokağın karşısından cepheye bakan düz, tek nokta perspektifli plan.

---

## 4. TEMA / KONU 2 — Kesirleri Karşılaştırma
### Hikaye: "Adalet Terazisi" (`tema4-konu2-kesir-karsilastirma/`)

**SAHNE SABİTLERİ (her prompta aynen ekle):** Sayfa 1-2 MÜBECCEL TEYZE'NİN EVİ'nin önündeki avluda doğum günü partisi: uzun masa, beyaz dantel örtü, renkli balonlar, İKİ PASTA — soldaki kahverengi çikolatalı (8 eş dilime bölünmüş), sağdaki pembe çilekli (10 eş dilime bölünmüş); dilim çizgileri NET görünür. Sayfa 3-4 çarşıda geçer: bir yanda NALBUR DÜKKÂNI (tanımı yapıştır), karşısında YENİ MARKET — modern, parlak, camlı cephe, önünde renkli balonlar ve boş beyaz pankart. Matematik odağı: dilim boyutu kontrastı ve fiyat etiketleri (etiketler boş renkli kartlar, yazı/rakam YOK). Görsellerde hiçbir yazı/rakam yok.

### 1) `assets/t4k2_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN tanımı] Doğum günü masasının başında KAHRAMAN; önünde iki pasta: 8 dilimli çikolatalı ve 10 dilimli çilekli (dilim çizgileri ve dilim boyutu farkı NET). İki elinde birer tabak, her tabakta üçer dilim — soldaki dilimler gözle görülür şekilde İRİ, sağdakiler İNCE. Yüzünde "bunlar eşit mi şimdi?" ifadesi, kaşlar havada. Arkada balonlar ve bulanık parti kalabalığı. Alt üçte birlik alan başlık için sade. Kamera: masa hizasından, iki tabak odakta.

### 2) `assets/t4k2_sayfa1.png` — Doğum günü ve dilim kavgası
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, MÜBECCEL TEYZE, EMRE, AYŞE, ELİF tanımları] Avluda parti: masada iki pasta (8 ve 10 dilimli), balonlar, çay bardakları. Merkezde EMRE ve AYŞE karşı karşıya, ikisi de elinde üçer dilimli tabak; EMRE kendi ince dilimlerini işaret edip itiraz ediyor, AYŞE'nin iri dilimli tabağına bakıyor — iki tabağın dilim boyu farkı görselin odağı. MÜBECCEL TEYZE masanın başköşesinde, doğum günü kızı edasıyla, kaşları havada hakem gibi izliyor. KAHRAMAN arada kalmış, elinde pasta bıçağı (doğal tutuş). ELİF gülümseyerek olayı çözmeye hazırlanıyor. Kamera: masayı gösteren 45 derece üstten.

### 3) `assets/t4k2_sayfa2.png` — Dedenin dilim dersi
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, EMRE, ELİF tanımları] Parti masasının başı, ikindi ışığı. Görselin odağı: DEDE'nin önüne aldığı İKİ TABAK — solda 3 İRİ dilim (8'lik pastadan), sağda 3 İNCE dilim (10'luk pastadan); boyut farkı abartılı ve net. DEDE iki eliyle iki tabağı terazi kefesi gibi havada dengeliyor (terazi jesti!). EMRE resmî olarak haklı çıkmış, ayağa kalkmış, gururlu. ELİF parmağıyla ince dilimleri sayıyor. KAHRAMAN deftere not alıyor. Kamera: masa hizasından yakın plan.

### 4) `assets/t4k2_sayfa3.png` — Market karşılaştırma seferberliği
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, EMRE tanımları + NALBUR DÜKKÂNI tanımı] Çarşı sokağı: solda NALBUR DÜKKÂNI, sağda YENİ MARKET (modern camlı cephe, balonlar, boş beyaz pankart). Ortada kaldırımda KAHRAMAN ve ELİF; KAHRAMAN açık defterine yazıyor, ELİF iki eliyle iki marketi karşılaştırır gibi işaret ediyor. EMRE market vitrinindeki boş fiyat etiketine burnunu dayamış bakıyor, kafasının üstünde soru işareti hissi (işaret YOK, sadece şaşkın ifade). İki dükkânın vitrinlerinde renkli ama YAZISIZ fiyat kartları. Kamera: sokağın ortasından iki cepheyi de gösteren geniş plan.

### 5) `assets/t4k2_sayfa4.png` — Pano ve terazi sınavı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, MUHTAR, MÜBECCEL TEYZE tanımları] Muhtarlık binasının önü, altın saat. Duvardaki büyük ahşap İLAN PANOSUNA asılmış geniş beyaz liste kâğıdı (üzerinde yazı yerine renkli satır çizgileri); önünde kuyruk olmuş mahalleli. KAHRAMAN panonun yanında, elinde defteriyle listeyi gösteriyor. MUHTAR elinde mühürlü zarf, resmî duruşta (megafon YOK). DEDE kapı önünden memnun izliyor. BALKON'da MÜBECCEL TEYZE alkışlıyor. Kamera: panoyu merkeze alan göz hizası plan.

---

## 5. TEMA / KONU 1 — İstatistiksel Araştırma ve Anket
### Hikaye: "Mahalle Anketi" (`tema5-konu1-istatistik-anket/`)

**SAHNE SABİTLERİ (her prompta aynen ekle):** Hikaye MEYDAN'da (tanımı yapıştır) ve mahalle sokaklarında geçer. Yeni sabit mekân: PARK — meydanın yanında, alçak çitli, salıncaklı küçük park; bir köşesi belirgin şekilde BOŞ toprak alan. Anket gereçleri her karede aynı: sert kapaklı KLİPSLİ PANO (üzerine takılmış beyaz kâğıt, kâğıtta yazı yerine renkli kutucuklar ve çizgi grupları) ve sarı kalem. Görsellerde hiçbir yazı/harf/rakam yok; çeteleler soyut çizgi grupları olarak çizilir.

### 1) `assets/t5k1_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN tanımı] Mahalle sokağında KAHRAMAN, bir elinde klipsli anket panosu, diğer elinde sarı kalem, kararlı sunum pozunda kameraya bakıyor. Arkasında hafif bulanık: bir kapı eşiğinde cevap veren komşu ve sırada bekleyen evler. Panodaki kâğıtta dört renkli seçenek kutusu ve yanlarında çetele çizgileri (yazı yok). Alt üçte birlik alan başlık için sade. Kamera: hafif alçak açı, pano net.

### 2) `assets/t5k1_sayfa1.png` — Meydan tartışması
> ⚠️ ÇOK ÖNEMLİ: Görselin HİÇBİR yerinde harf, kelime, yazı, etiket OLMAYACAK — konuşma balonu içinde bile yazı YOK, sadece resim. Negatif: text, letters, words, labels, captions, signs with writing.
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, MUHTAR, DEDE, EMRE, MÜBECCEL TEYZE tanımları + BALKON tanımı] MEYDAN kalabalık ve kaotik-komik: EMRE havaya basket atar gibi zıplıyor, iki küçük çocuk kaydırak kayar gibi poz yapıyor, DEDE elinde bir saksı çiçekle sakin duruyor, BALKON'da MÜBECCEL TEYZE bank oturuşu taklidi yapıyor. Herkesin üstünde kendi isteğini gösteren küçük düşünce balonları — balonların içinde SADECE ÇİZİM var: basket topu, salıncak, ahşap bank, çiçek; kesinlikle harf veya kelime yok. Arka planda PARK ve boş toprak köşesi (köşe sadece boş toprak olarak resmedilir, üzerinde etiket yok). MUHTAR hoparlör direğinin altında megafonuyla anons ediyor; megafonundan çıkan ses SADECE ses dalgası çizgileriyle gösterilir, konuşma balonu YOK. KAHRAMAN sahnede YALNIZCA BİR KEZ görünür: kenarda defterini açmış izliyor. Kamera: geniş plan.

### 3) `assets/t5k1_sayfa2.png` — Soru yazma dersi
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, EMRE, DEDE tanımları + NALBUR DÜKKÂNI tanımı] Nalbur önündeki tezgâh; EMRE elinde buruşturulmuş üç kâğıt topu, mahcup ama gülümsüyor; önünde çöpe atılmış iki kâğıt topu daha. ELİF ayakta, öğretmen edasıyla parmak sallıyor. Masada temiz bir kâğıt: üzerinde dört renkli seçenek kutusu (yazısız). KAHRAMAN kâğıda son düzeltmeyi yapıyor. DEDE arkada onaylayarak izliyor. Kamera: tezgâh hizası.

### 4) `assets/t5k1_sayfa3.png` — Kapı kapı anket
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, MÜBECCEL TEYZE tanımları + BALKON tanımı] Mahalle sokağı, öğleden sonra. Ön planda bir kapı eşiği: KAHRAMAN panoyu tutuyor, kapıdaki güler yüzlü komşu kadın parmağıyla panodaki seçeneklerden birini gösteriyor; ELİF çetele çiziyor. Sokağın ilerisinde NECMİ kargo kolisini bırakmış, sırada oy bekliyor. BALKON'da MÜBECCEL TEYZE eliyle "hepsi" der gibi dört parmağını açmış, kararsız-komik ifade. Kamera: kapı önü yakın plan, sokak derinliği.

### 5) `assets/t5k1_sayfa4.png` — Sayım ve ilan
> ⚠️ ÇOK ÖNEMLİ: Görselin HİÇBİR yerinde harf, kelime, yazı OLMAYACAK — tabloda başlık yazısı YOK, konuşma balonu YOK. Negatif: text, letters, words, labels, table headers, captions. Ayrıca KAHRAMAN (yeşil tişörtlü kıvırcık çocuk) sahnede YALNIZCA BİR KEZ görünür — kopyası, benzeri, ikizi OLMAZ.
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, EMRE, AYŞE, MUHTAR tanımları] Akşamüstü, nalbur tezgâhında sayım: masaya serilmiş anket kâğıtları (üzerlerinde yazı yerine soyut kısa çizgiler), ortada büyük beyaz kâğıtta DÖRT SATIRLI TABLO — tabloda başlık satırı YOK; her satırda solda bir seçenek ÇİZİMİ (salıncak / basket topu / bank / çiçek), ortada çetele demetleri (dört dik çizgi + bir çapraz), sağda küçük renkli nokta grupları. Tabloda kesinlikle harf ve rakam yok. Masanın başında DÖRT çocuk: merkezde KAHRAMAN (tek!), yanında ELİF, karşısında EMRE ve AYŞE — başlar bir arada, sayım heyecanı. Arka planda MUHTAR hoparlör direğinin altında megafonla ilan ediyor; ses, dalga çizgileriyle gösterilir, konuşma balonu yok; birkaç komşu sevinçle dinliyor. Kamera: tezgâhı odaklayan 45 derece üstten, arka plan derinlikli.

---

## 5. TEMA / KONU 2 — Veri Görselleştirme
### Hikaye: "Yalancı Grafik" (`tema5-konu2-grafikler/`)

**SAHNE SABİTLERİ (her prompta aynen ekle):** Hikaye muhtarlık İLAN PANOSU önünde ve çarşıda (NALBUR + YENİ MARKET karşılıklı) geçer. Grafikler her karede geometrik olarak DOĞRU çizilir: sütun grafikleri dört renkli sütun (yeşil, turuncu, mavi, kırmızı), eşit genişlik ve aralıkta; daire grafiği dört renkli dilimli. Grafiklerde ve görselin hiçbir yerinde HARF/RAKAM/YAZI YOK — eksen değerleri yerine küçük çentik çizgileri kullanılır. ⚠️ KAHRAMAN her sahnede YALNIZCA BİR KEZ görünür.

### 1) `assets/t5k2_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN tanımı] Muhtarlık önündeki büyük ahşap İLAN PANOSU; panoya asılı dev beyaz kâğıtta DÖRT RENKLİ SÜTUNLU dürüst grafik (yeşil, turuncu, mavi, kırmızı; mavi sütun en uzun; eksen çizgileri net, yazı yok). KAHRAMAN panonun önünde, elinde büyük fırça/kalın keçeli kalem, son sütunu bitirmiş, gururla izleyiciye dönmüş. Yerde boya kutuları ve cetvel. Alt üçte birlik alan başlık için sade. Kamera: panoyu ve kahramanı gösteren hafif alçak açı.

### 2) `assets/t5k2_sayfa1.png` — Dev grafik çizimi
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, MUHTAR tanımları] İlan panosu önü, sabah. KAHRAMAN merdivene çıkmış, panodaki dev kâğıda cetvelle DÖRDÜNCÜ sütunu (kırmızı, yarısı boyalı) bitiriyor; kâğıtta TAM DÖRT sütun var: yeşil, turuncu, mavi (EN UZUN), kırmızı. ⚠️ Sütun sayısı KESİNLİKLE DÖRT. Negatif: three bars, five bars. ELİF aşağıda elinde renk kutularıyla yönetiyor, parmağıyla hizayı gösteriyor. MUHTAR kenarda ellerini arkasında kavuşturmuş, memnun süzüyor (megafon YOK). Grafikte eksen çizgileri ve çentikler var, yazı yok. Kamera: panoyu geniş gösteren plan.

### 3) `assets/t5k2_sayfa2.png` — Daire grafiği ve pasta
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, MÜBECCEL TEYZE tanımları] Pano önü; panoda iki kâğıt yan yana: solda sütun grafiği, sağda YENİ çizilmiş büyük DAİRE GRAFİĞİ — dört renkli dilim (mavi dilim en büyük, dairenin üçte biri kadar). MÜBECCEL TEYZE (balkonda değil, panonun önünde!) memnun, eliyle büyük mavi dilimi gösteriyor. ELİF pergelle daireyi tamamlamış. KAHRAMAN boya fırçasını yıkıyor. Kamera: panoya yakın, iki grafik net.

### 4) `assets/t5k2_sayfa3.png` — Vitrindeki yalancı grafik
> ⚠️ Bu sahne YENİ MARKET vitrini önünde, DIŞ mekânda geçer. ⚠️ HER KARAKTER SAHNEDE YALNIZCA BİR KEZ görünür — sarı elbiseli kız (ELİF) TEK'tir, ikinci bir kız çocuğu YOKTUR. Negatif prompt: duplicate character, twins, identical girls, clones. [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, EMRE tanımları] Marketin camlı vitrininde kocaman bir grafik afişi: SADECE İKİ sütun — biri KISACIK (yeşil), biri GÖKDELEN gibi uzun (kırmızı); fark abartılı ve orantısız, grafiğin alt kısmı kesik görünümlü (eksen kırpılmış hissi — zikzaklı kesik çizgiyle). ELİF cam önünde eğilmiş, parmağıyla grafiğin ALT kenarındaki kesik zikzak bölgeyi gösteriyor — "tuzak burada" jesti. KAHRAMAN defterine not alıyor. EMRE şaşkın, iki eli başında. Kamera: vitrine yakın plan, afiş odakta.

### 5) `assets/t5k2_sayfa4.png` — İki grafik yan yana
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, EMRE tanımları] İlan panosunda YAN YANA iki grafik kâğıdı: solda marketin abartılı grafiği (kısa-uzun orantısız iki sütun, altı kesik), sağda DÜRÜST versiyon (aynı iki sütun ama neredeyse eşit boyda, eksen tam). İkisinin kontrastı görselin odağı. Panonun önünde toplanan mahalleli gülümseyerek karşılaştırıyor. KAHRAMAN dürüst grafiği eliyle gösteriyor. DEDE kenarda market sahibine (kısa boylu, mahcup, önlüklü esnaf) çay uzatıyor — barışma anı. Kamera: panoyu merkeze alan göz hizası.

---

## 6. TEMA / KONU 1 — Eşitlik, İşlem Özellikleri ve İşlem Önceliği
### Hikaye: "Dede'nin Terazisi" (`tema6-konu1-islem-ozellikleri/`)

**SAHNE SABİTLERİ (her prompta aynen ekle):** Hikaye mahalle ŞENLİĞİ günlerinde geçer: MEYDAN ve sokaklarda renkli üçgen flamalar asılıdır. Kilit obje: DEDE'nin ESKİ KEFELİ TERAZİSİ — pirinç/bakır renginde, iki yuvarlak kefesi zincirlerle asılı, ortada dik ibre; gerçekçi boyutta (masa terazisi). Terazinin dengede olduğu sahnelerde iki kefe TAM AYNI HİZADA. ⚠️ Görselin hiçbir yerinde harf/rakam/yazı YOK. ⚠️ HER KARAKTER sahnede YALNIZCA BİR KEZ görünür. Negatif prompt: text, letters, numbers, labels, duplicate character, twins, clones.

### 1) `assets/t6k1_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE tanımları] NALBUR DÜKKÂNI önü, şenlik flamaları. Ahşap tezgâhın üstünde DEDE'nin pirinç kefeli terazisi, TAM DENGEDE; iki kefede eşit boyda birer madeni ağırlık. DEDE terazinin arkasında, elleri tezgâhta, gururlu-bilge gülümseme. KAHRAMAN öne eğilmiş, teraziyi hayranlıkla inceliyor, kulağının üstünde sarı kalem. Sıcak akşamüstü ışığı. Alt üçte birlik alan başlık için sade. Kamera: tezgâh hizasından, terazi odakta.

### 2) `assets/t6k1_sayfa1.png` — Halat çekme ve denge
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, MUHTAR tanımları] Şenlikli MEYDAN; ortada tebeşirle çizilmiş çizgi, iki yanda kalın halatı çeken iki ÇOCUK TAKIMI (her takımda 5 farklı çocuk; iki takım kütlece dengeli görünür, halat gergin ve TAM ORTADA). KAHRAMAN kenarda hakem: elinde açık kareli defter, ciddi bir ifadeyle izliyor. DEDE arkada kasketiyle, kollarını kavuşturmuş keyifle seyrediyor. MUHTAR başlangıç işareti verir gibi elini kaldırmış (megafon YOK). Kamera: halatı yandan gösteren geniş plan, simetri vurgulu.

### 3) `assets/t6k1_sayfa2.png` — Nalburda torbalar (dağılma özelliği)
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE tanımları] NALBUR DÜKKÂNI içi, ahşap tezgâh. Tezgâhta YAN YANA DÖRT EŞ bez torba; her torbanın önünde küçük bir küme: 5 parlak vida + 2 altıgen somun (dört kümede de aynı düzen — geometrik olarak DOĞRU: 4 grup × 7 parça). DEDE bir torbayı doldururken KAHRAMAN defterine bakıp şaşkın-hayran; kulağında sarı kalem. Raflarda kovalar, ipler, süpürgeler. Sıcak dükkân ışığı. Kamera: tezgâha üstten hafif açılı, dört torba ve kümeler net.

### 4) `assets/t6k1_sayfa3.png` — Baklava tepsisi ve küp şeker (kare-küp)
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, EMRE, KADİR USTA tanımları] FIRIN önündeki uzun ahşap masa. Masada iki odak: solda KARE metal baklava tepsisi — ⚠️ TAM 6 SIRA × 6 SÜTUN = 36 EŞİT kare dilim; ızgara dümdüz, eşit aralıklı, üstten bakışta sayılabilir NET. Negatif: irregular grid, uneven slices, 4 rows, 5 rows; sağda açık bir karton kutuda 3×3×3 istiflenmiş beyaz küp şekerler (üst katman görünür, küp düzeni net). ELİF parmağıyla tepsinin sıra-sütunlarını gösteriyor. EMRE küp şeker kutusuna kafasını sokacak kadar yaklaşmış, komik meraklı. KADİR USTA (önlüklü, güler yüzlü fırıncı) elinde hamur ruleti, eller anatomik doğru. KAHRAMAN defterine çiziyor. Kamera: masaya yakın, tepsi ve kutu odakta.

### 5) `assets/t6k1_sayfa4.png` — Bakkal önünde işlem tartışması
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, EMRE, NECMİ tanımları] Bakkal dükkânı önü, akşamüstü; şenlik flamaları. Kapı önünde toplanmış mahalleli İKİYE bölünmüş: solda üç kişi Emre'nin yanında, sağda üç kişi bakkalın yanında; iki grup birbirine dönük tatlı-sert tartışıyor (eller havada, komik jestler). Ortada EMRE elinde küçük beyaz kâğıt fiş (üzerinde yazı YOK, sadece boş kâğıt) — bir simit ve iki süt şişesi de tezgâhta görünür. DEDE tam ortada, bir eli havada trafik polisi gibi "dur" işareti yapıyor — bilge ve sakin. NECMİ (önlüklü bakkal) kapıda mahcup. KAHRAMAN kenarda gülümseyerek defterine not alıyor. Kamera: grubu önden alan göz hizası, DEDE odakta.

---

## 6. TEMA / KONU 2 — Sayı ve Şekil Örüntüleri
### Hikaye: "Halının Şifresi" (`tema6-konu2-oruntuler/`)

**SAHNE SABİTLERİ (her prompta aynen ekle):** Şenlik SONRASI günler; flamalar hâlâ yer yer asılı. Kilit obje: MÜBECCEL TEYZE'nin ASIRLIK KİLİMİ — kırmızı-lacivert zeminli el dokuması; deseninde SOLDAN SAĞA hiç şaşmadan tekrar eden sıra: KARE, ÜÇGEN, YILDIZ, KARE, ÜÇGEN, YILDIZ... (geometrik olarak düzgün, tekrar net görünür). ⚠️ Görselin hiçbir yerinde harf/rakam/yazı YOK. ⚠️ HER KARAKTER sahnede YALNIZCA BİR KEZ görünür. Negatif prompt: text, letters, numbers, labels, duplicate character, twins, clones.

### 1) `assets/t6k2_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF tanımları] MÜBECCEL TEYZE'nin BALKONU'ndan aşağı sarkıtılmış asırlık kilim, görselin ana yüzeyi; kare-üçgen-yıldız deseni tekrarı NET okunuyor. KAHRAMAN sokakta, kilime hayranlıkla bakıyor, kulağında sarı kalem. ELİF parmağıyla desendeki tekrarı takip ediyor. Sıcak sabah ışığı, begonviller. Alt üçte birlik alan başlık için sade. Kamera: kilimi tam gösteren hafif alçak açı.

### 2) `assets/t6k2_sayfa1.png` — Balkonda kilim silkeleme
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, MÜBECCEL TEYZE, DEDE tanımları] BALKON sahnesi: MÜBECCEL TEYZE (dürbün boynunda ASILI, kullanmıyor) balkon korkuluğundan kilimi silkeliyor; kilimin deseni (kare-üçgen-yıldız tekrarı) izleyiciye dönük ve net. Aşağıda sokakta KAHRAMAN ve ELİF yukarı bakıyor; ELİF eliyle desenleri sayar gibi. DEDE kapı önünde taburede çay bardağıyla, bilge gülümseme. Toz bulutu komik detay. Kamera: sokaktan balkona bakan açı.

### 3) `assets/t6k2_sayfa2.png` — Kumbara ve bisiklet hayali
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, EMRE tanımları] MEYDAN'daki taş çeşmenin kenarı. EMRE ortada, kucağında toprak kumbara, gözleri parlıyor; başının üstünde düşünce balonu gibi hafif saydam parlak KIRMIZI BİSİKLET hayali (balon çizgisi yok, sadece havada hafif saydam bisiklet — ⚠️ bisikletin üzerinde ve çevresinde YAZI/BAŞLIK YOK). ELİF yanında yere tebeşirle EŞİT ARALIKLI, GİDEREK UZAYAN çubuk sıraları çiziyor (örüntü hissi: 1 çubuk, 2 çubuk, 3 çubuk...). KAHRAMAN defterine yazıyor. Çeşmenin başında iki tekir kedi. Kamera: çeşme kenarına yakın göz hizası. Negatif prompt: text, letters, captions, titles.

### 4) `assets/t6k2_sayfa3.png` — Kürdanlarla kare örüntüsü
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, EMRE, KADİR USTA tanımları] FIRIN önündeki uzun ahşap masa. Masanın üstünde kürdanlardan yapılmış BİTİŞİK KARE ZİNCİRİ üç ayrı örnek: solda TEK kare (4 kürdan), ortada 2 bitişik kare (ortak dikey kenar, 7 kürdan), sağda sıra hâlinde 3 bitişik kare (10 kürdan). ⚠️ Kürdanlar DÜZGÜN, DİK AÇILI ve HİZALI — çapraz, eğik veya üst üste binmiş kürdan YOK; kareler kusursuz. Fırın tabelası BOŞ ahşap levha. Negatif prompt: crooked sticks, overlapping sticks, diagonal sticks. KADİR USTA (önlüklü, güler yüzlü) elinde kürdan kutusu, meydan okuyan neşeli bakış. EMRE masaya eğilmiş kürdanları işaret ederek sayıyor. ELİF bir elini havaya kaldırmış "buldum" hâlinde. KAHRAMAN defterine yazıyor. Kamera: masaya üstten hafif açılı, kürdan zinciri odakta.

### 5) `assets/t6k2_sayfa4.png` — Meydanda fener sıraları
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, MUHTAR, DEDE tanımları] Akşamüstü MEYDAN; gökyüzüne gerilmiş iplerde sıra sıra renkli kâğıt fenerler: EN ÖNDEKİ ipte 3 fener, arkasındakinde 6, daha arkada 9 — sıralar arttıkça fener sayısı belirgin şekilde artıyor (örüntü hissi net). Aşağıda MUHTAR elinde kâğıt-kalem, saçı başı dağılmış, bunalmış hâlde fenerleri parmağıyla sayıyor (megafon YOK). KAHRAMAN yanında sakin, defterini göstererek açıklıyor. DEDE arkada kasketini düzeltiyor, gururlu. Merdivenli elektrikçi ustası ipin başında bekliyor. Sıcak fener ışıkları. Kamera: fener sıralarını perspektifle gösteren geniş plan.

---

## 7. TEMA — Veriden Olasılığa (SERİ FİNALİ)
### Hikaye: "Şans Torbası" (`tema7-olasilik/`)

**SAHNE SABİTLERİ (her prompta aynen ekle):** PANAYIRIN SON GÜNÜ: meydan ve sokaklarda renkli flamalar + kâğıt fenerler birlikte asılı, şenlikli kapanış havası. Kilit objeler: (1) ÇEKİLİŞ TORBASI — bordo kadife, büzgülü ağızlı, orta boy bez torba; (2) ödül KIRMIZI BİSİKLET — parlak, kurdeleli; (3) OLASILIK SPEKTRUM İPİ — iki ahşap kazık arasına gerilmiş ip, bir ucunda KIRMIZI kurdele, diğer ucunda YEŞİL kurdele, üzerinde tahta mandallar. ⚠️ Görselin hiçbir yerinde harf/rakam/yazı YOK. ⚠️ HER KARAKTER sahnede YALNIZCA BİR KEZ görünür. Negatif prompt: text, letters, numbers, labels, duplicate character, twins, clones.

### 1) `assets/t7k1_kapak.png` — Kitap kapağı
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN tanımı] Panayır meydanında ahşap sehpanın üstünde büzgülü bordo kadife ÇEKİLİŞ TORBASI, hafif ışıltılı; hemen arkasında kurdeleyle süslenmiş parlak KIRMIZI BİSİKLET sergileniyor — ⚠️ kadrosu DÜZ KIRMIZI: marka, etiket, yazı, logo YOK. Negatif: logo, brand name, decals, stickers. KAHRAMAN torbanın yanında, bir eli torbada, izleyiciye dönük heyecanlı-gizemli gülümseme; kulağında sarı kalem. Arka planda flamalar ve fenerler, alacakaranlık şenlik ışıkları. Alt üçte birlik alan başlık için sade. Kamera: sehpa hizasından, torba ve bisiklet odakta.

### 2) `assets/t7k1_sayfa1.png` — Çekiliş duyurusu
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, EMRE, MUHTAR tanımları] Panayır MEYDANI; MUHTAR küçük ahşap platformda, MEGAFONLA gerçekten anons yapıyor (bu sahnede megafon VAR); yanındaki sehpada çekiliş torbası ve kurdeleli kırmızı bisiklet. Önde kalabalık içinde EMRE iki kolunu havaya kaldırmış, kendinden emin, zafer pozunda. ELİF yanında kaşı kalkık, kuşkucu bakış. KAHRAMAN defterine not alıyor. Kamera: kalabalığın arasından platforma bakan açı.

### 3) `assets/t7k1_sayfa2.png` — İpte olasılık spektrumu
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, ELİF tanımları] NALBUR DÜKKÂNI önü, sabah. İki ahşap kazık arasına gerilmiş SPEKTRUM İPİ: sol ucunda KIRMIZI kurdele, sağ ucunda YEŞİL kurdele; ip üzerinde üç tahta mandal — biri kırmızı uca yakın, biri TAM ORTADA, biri yeşil uca yakın (mandallarda yazı yok). KAHRAMAN elinde bir mandalla ipin ortasına uzanıyor. DEDE kasketiyle yanında, eliyle yeşil ucu gösteriyor, öğretici hâl. ELİF izliyor. Arka planda çitin üstünde kızıl HOROZ gıcık bir ifadeyle ötüyor. Kamera: ipi boydan boya gösteren yan açı.

### 4) `assets/t7k1_sayfa3.png` — Torbadan top çekme deneyi
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, ELİF, EMRE tanımları] Bakkal önündeki küçük masa. Masada ağzı açık bez torba; yanında masaya dizilmiş toplar: ÜÇ KIRMIZI top bir arada, BİR SARI top ayrı (sayılar net: 3 kırmızı + 1 sarı). EMRE gözleri bantla DEĞİL eliyle kapalı, diğer elini torbaya daldırmış, komik gergin ifade. ELİF kollarını kavuşturmuş bilgiç gülümseme. KAHRAMAN defterine çetele işareti çizer gibi not tutuyor (defter sayfası uzakta, yazı okunmaz). Kamera: masaya yakın göz hizası, toplar odakta.

### 5) `assets/t7k1_sayfa4.png` — Adil olmayan renk küpü
> [ORTAK STİL + SAHNE SABİTLERİ + KAHRAMAN, DEDE, EMRE, NECMİ'NİN YEĞENİ tanımı: 20'li yaşlarda, jölesiz dağınık saçlı, modern gömlekli, mahcup genç] Panayır OYUN STANDI: ahşap tezgâh, üstünde kocaman RENK KÜPÜ — görünen üç yüzünden İKİSİ MAVİ, BİRİ KIRMIZI (mavi ağırlığı hissedilir); yanında bir kâsede lokumlar. KAHRAMAN küpü havaya kaldırmış, yüzlerini gösteriyor — "yakaladım" hâli. EMRE yanında bitkin, yedi kayıp sonrası dramatik çökük omuzlar. NECMİ'NİN YEĞENİ tezgâh arkasında kıpkırmızı, mahcup. DEDE kenarda sakin, bir parmağı havada ders verir gibi. Fener ışıkları sıcak. Kamera: standı önden alan göz hizası, küp odakta.

---

**🎉 SERİ TAMAM:** 7 tema, 14 konu klasörü, 15 unvan. Tüm görseller üretildiğinde "Mahalle Matematiği" projesi eksiksiz olacak.
