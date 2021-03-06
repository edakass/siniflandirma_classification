SINIFLANDIRMA

Sınıflandırma isimli bir klasör oluşturdum.
![image](https://user-images.githubusercontent.com/61595808/111068231-fef1e480-84d8-11eb-9470-9377cc6d3789.png)
![image](https://user-images.githubusercontent.com/61595808/111068237-04e7c580-84d9-11eb-8fe2-46f77e4b476b.png)
Test klasörü :
![image](https://user-images.githubusercontent.com/61595808/111068260-16c96880-84d9-11eb-9269-fb98ef370fbb.png)
Kolye :
![image](https://user-images.githubusercontent.com/61595808/111068276-26e14800-84d9-11eb-8deb-8fe4b63208b7.png)
Roman :
![image](https://user-images.githubusercontent.com/61595808/111068280-2fd21980-84d9-11eb-8e39-851e82fffc88.png)
Train Klasörü:
Kolye:
![image](https://user-images.githubusercontent.com/61595808/111068290-424c5300-84d9-11eb-9a98-718c182a4792.png)
Roman:
![image](https://user-images.githubusercontent.com/61595808/111068296-4b3d2480-84d9-11eb-8f59-4720108eae3e.png)
Anaconda da Environments kısmında keras ve opencv yüklü gelmediği için ayrıyetten cmd  kısmından yüklemem gerekti.O yüzden bir çok sitedeki durumları denedim.
Mesela Opencv kütüphanesi için şu adımları gerçekleştirdim:
conda install -c conda-forge opencv 
Python
import cv2
cv2.__version__
(İlk seferde yüklediğim de bu şekilde geldi en son sefer de ise bu adımlardan önce 

Pythonın kendi idesi için.
pip install opencv-python

Kaynak:https://medium.com/aattk/opencv-kurulumu-windows-python-ffe807b0e827

Bu kısmıda yükleyip en baştaki kodları denedim opencv kütüphanesini tanıyor ama 
diğer kısımları bir hata var yazıp inmiyordu.
Keras Kütüphanesi için:

conda install -c conda-forge keras
Enter dedikten sonra,indirme işlemi bittiğinde.Bir soru karşımıza çıkıyor:
y/n 
Bu soruya y dedikten sonra indirme işlemim gerçekleşti. 
Tenserflow için ise :
conda install -c conda-forge tensorflow
Yine y/n sorusu 
y cevabı.
Ve indirme işlemlerimin tamamını gerçekleştirdim.

![image](https://user-images.githubusercontent.com/61595808/111068432-c3a3e580-84d9-11eb-8123-89e764d58cf2.png)
![image](https://user-images.githubusercontent.com/61595808/111068440-c7d00300-84d9-11eb-9e22-7ead45a10098.png)
![image](https://user-images.githubusercontent.com/61595808/111068453-d5858880-84d9-11eb-857b-884940625111.png)
![image](https://user-images.githubusercontent.com/61595808/111068460-db7b6980-84d9-11eb-9ff9-e7016e227662.png)
![image](https://user-images.githubusercontent.com/61595808/111068466-e0d8b400-84d9-11eb-9216-17c703c65d06.png)
![image](https://user-images.githubusercontent.com/61595808/111068469-e504d180-84d9-11eb-8309-b712a6c7911a.png)
![image](https://user-images.githubusercontent.com/61595808/111068477-ea621c00-84d9-11eb-8acf-4023ff48993b.png)
![image](https://user-images.githubusercontent.com/61595808/111068480-ee8e3980-84d9-11eb-88d3-a4fe0eb610d5.png)
![image](https://user-images.githubusercontent.com/61595808/111068483-f221c080-84d9-11eb-817c-ce14ef90abca.png)
![image](https://user-images.githubusercontent.com/61595808/111068487-f9e16500-84d9-11eb-859c-6975b2f85d04.png)
![image](https://user-images.githubusercontent.com/61595808/111068490-fd74ec00-84d9-11eb-9b48-118a3fce3c02.png)
![image](https://user-images.githubusercontent.com/61595808/111068497-02d23680-84da-11eb-805d-717fcb2cb4fd.png)
![image](https://user-images.githubusercontent.com/61595808/111068499-06fe5400-84da-11eb-9b50-f27d4a9ec5b8.png)
![image](https://user-images.githubusercontent.com/61595808/111068501-0a91db00-84da-11eb-95a8-39c5cf606337.png)
![image](https://user-images.githubusercontent.com/61595808/111068503-0d8ccb80-84da-11eb-8b5f-2c3c184bbaab.png)
![image](https://user-images.githubusercontent.com/61595808/111068504-11b8e900-84da-11eb-8126-2554fe08cae9.png)
![image](https://user-images.githubusercontent.com/61595808/111068509-14b3d980-84da-11eb-9173-879d7c8251d4.png)
![image](https://user-images.githubusercontent.com/61595808/111068513-18476080-84da-11eb-9ab2-0151a67b93eb.png)


İlk kısımlarda gerekli olan kodları kullanıp yazdıktan sonra ki kısımda  Transfer Öğrenmeyi kullandım.

![image](https://user-images.githubusercontent.com/61595808/111067519-c00e5f80-84d5-11eb-8618-9cb4e7736c5d.png)

Transfer Öğrenme/Aktarımı-Transfer Learning

Günlük hayatımızda bir durumda öğrendiğimiz bir bilgiyi sık sık başka bir durumda kullanarak o bilgiyi başka bir konu üzerine aktarırız. Karşılaştığımız durumların benzer olması bizim o bilgiyi aktarmamıza kolaylık sağlar. Örneğin bisiklet kullanabilen birinin araba kullanmayı öğrenmesi bisiklet kullanamayan birine göre daha kolay ve hızlı olabilir. Birbirine benzer olan bu olaylarda kişi bisiklet sürmeyi öğrendiği sırada kazandığı araç kontrol etme becerisini araba sürerken kullanmakta ve farkında olmadan öğrenme aktarımı yapmaktadır.

Öğrenme aktarımı (Transfer learning) makine öğrenmesi yöntemlerinin de aynı bizim gibi bir problemi çözerken elde ettiği bilgiyi saklayıp, başka bir problem ile karşılaştığında o bilgiyi kullanmasıdır. Öğrenme aktarımı ile önceki bilgiler kullanılarak daha az eğitim verisi ile daha yüksek başarı gösteren ve daha hızlı öğrenen modeller elde edilir.

![image](https://user-images.githubusercontent.com/61595808/111067579-0237a100-84d6-11eb-90fd-c0d77c3162aa.png)

Normalde makine öğrenmesinde her bir görev için ayrı bir ‘sıfırdan öğrenme’ gerçekleştirilir. Ancak bazı görevlerden öğrenilen bir takım bilgileri başka görevlerde de kullanmak mümkün ve avantajlı olacağından kaynak görevlerden elde edilen bilgi hedef görevin çözümü için kullanılmaktadır. Öğrenme aktarımı ile daha önceden eğitilmiş modellerden elde edilen özellikler, ağırlıklar vb. yeni bir görev için kullanılmaktadır. Bu yöntemin işe yaraması için aktarılacak bilgilerin genel bilgiler olması gerekir, yani kaynak göreve özgü olmak yerine hem kaynak hem de hedef görevler için uygun olan bilgiler aktarılır.

Örneğin, bilgisayarla görme alanında kedi ile köpeği ayırt edebilen bir modelde elde ettiğimiz bilgileri 2 farklı hedef görevde kullanmayı düşünelim. Birincisi motosiklet, bisiklet vb. araç tanıma için ikincisi aslan, kaplan, at vb. diğer hayvanları tanıma olsun. Birinci görev için aktarılacak bilgi tahmin edileceği üzere ikinci görev için aktarılacak bilgi ile aynı olamaz. Birinci görev için öğrenme aktarımı yapıldığında aktarılan bilgi hemen hemen her görüntü üzerinde aynı olan düşük seviyeli özellikler, kenarlar, köşeler, şekillerdir. İkinci görev için öğrenme aktarımı yapıldığında ise kedi köpek tanımada keşfedilen göz, burun, kulak gibi karmaşık şekillerin de bilgisinin aktarılması gerekir.

![image](https://user-images.githubusercontent.com/61595808/111067592-167b9e00-84d6-11eb-845c-5335758e9fd4.png)

Öğrenme aktarımı sürecinde aşağıda verilen 3 soru sorulur:
![image](https://user-images.githubusercontent.com/61595808/111067628-3612c680-84d6-11eb-8da5-30e97d13d767.png)

*Öğrenme aktarımında kaynak görevi isteğimiz bilgileri öğrenecek şekilde kendimiz geliştirebiliriz veya hazır bir model kullanabiliriz. Uygulamada daha çok tercih edilen yöntem ikincisidir. Bu tarz uygulamaların en güzel örneklerinden biri ImageNet yarışmasıdır. Bu yarışmada 1000 sınıflı fotoğrafları sınıflandırma gibi büyük ve zorlu bir görüntü sınıflandırma görevi vardır. Bu yarışma için modeller geliştiren araştırma kuruluşları genellikle son modellerinin bir lisans kapsamında yeniden kullanılmasına izin vermektedir. Bu modellerin modern donanımlar ile eğitilmesinin günler veya haftalar alabildiği düşünüldüğünde önceki yıl eğitilmiş en iyi modelin bir sonraki yılda öğrenme aktarımı ile kullanılması oldukça mantıklı ve yaygın bir uygulamadır.

Neden öğrenme aktarımını kullanalım?
*Daha hızlı eğitim süresi: Önceden eğitilmiş modellerdeki ağırlıklar birçok bilgiyi barındırmaktadır. Dolayısıyla bu bilgileri kullanıp ince ayar(fine-tuning) yapılarak yeni model daha hızlı eğitilir. Hatta bazı problemler için öğrenme aktarımı kullanılarak 2–4 epochta bile yüksek başarı elde edilebilmektedir.
*Daha az veri: Sıfırdan oluşturulan modellerin en büyük dezavantajı eğitim için büyük ölçekli bir veri kümesinin gerekmesidir. Bu veri kümelerinin oluşturulması için ciddi bir zaman gerekir. Bunun yerine önceden eğitilmiş modellere ince ayar yapılması daha az veri kullanarak yüksek performanslar elde edilmesini sağlar.
*Daha iyi performans: Önceden eğitilmiş modellere yeni tam bağlantılı katman(lar) eklenerek yapılan basit bir işlemin başarıyı iyileştirdiği görülmektedir.

Yöntemler Öğrenme aktarımı kaynak/hedef öğrenme görev ve verilerine göre üç grupta ifade edilir.
![image](https://user-images.githubusercontent.com/61595808/111067650-4fb40e00-84d6-11eb-82b3-484a196ac72d.png)

Bilgisayarla Görme
Bilgisayarla görme alanında öğrenme aktarımına örnek olarak ImageNet yarışması verilebilir.Doğal dil işleme uygulamalarında olduğu gibi bu alanda da büyük görüntü veri kümeleri ile önceden eğitilmiş hazır modeller bulunur. Bunlar indirilebilir ve doğrudan görüntü verilerinin girdi olarak verilebileceği yeni modellere dahil edilebilir. Burada tabi ki önceden de bahsetmiş olduğumuz gibi görev benzerliğine göre hangi katmana kadarki bilgilerin aktarılacağına dikkatli bir şekilde karar vermek gerekiyor. Derin öğrenme mimarileri:
      *Oxford VGG Model
      *Google Inception Model	
      *Microsoft ResNet Model
      *Caffe Model Zoo
  
 VGG
VGG (Visual Geometry Group) Oxford Üniversitesinde kurulan bir araştırma grubu olan (Visual Geometry Group)  kısaltılmış halidir.Vgg bu isimden gelmektedir.
Vgg 16 başarısı İmageNet yarışmasında %92.7 lik başarısıyla ispatlamıştı.
16 ve 19 katman sayılarını temsil ediyor.
Vgg genel olarak bir Convolution sinir ağının başarımın arttırmak için daha da derinleşmesi tekniğine dayanır.

VGG-16
*Basit bir ağ modeli olup öncesindeki modellerden en önemli farkı evrişim katmalarının 2’li ya da 3’li kullanılmasıdır. Tam bağlantı (FC) katmanında 7x7x512=4096 nöronlu bir öznitelik vektörüne dönüştürülür. İki FC katmanı çıkışında 1000 sınıflı softmax başarımı hesaplanır. Yaklaşık 138 milyon parametre hesabı yapılmaktadır. Diğer modellerde olduğu gibi girişten çıkışa doğru matrislerin yükseklik ve genişlik boyutları azalırken derinlik değeri (kanal sayısı) artmaktadır.

![image](https://user-images.githubusercontent.com/61595808/111067708-7eca7f80-84d6-11eb-8591-dd8b96d838a1.png)

![image](https://user-images.githubusercontent.com/61595808/111067714-84c06080-84d6-11eb-95da-cba5beb7f8ec.png)

![image](https://user-images.githubusercontent.com/61595808/111067720-8a1dab00-84d6-11eb-8c1c-acc750501d67.png)

![image](https://user-images.githubusercontent.com/61595808/111067727-8f7af580-84d6-11eb-9eb5-829ca1b6a173.png)

![image](https://user-images.githubusercontent.com/61595808/111067733-9570d680-84d6-11eb-906d-32494261d347.png)

Giriş katmanında 224'e 224 boyutunda görseller kullanılır.
Fotğrafalrımız renkli o yüzden Rgb olarak 3 katmandan oluşuyor.

![image](https://user-images.githubusercontent.com/61595808/111067741-a28dc580-84d6-11eb-8f4f-f093c21e7f76.png)

![image](https://user-images.githubusercontent.com/61595808/111067750-a883a680-84d6-11eb-8911-29535b389943.png)

![image](https://user-images.githubusercontent.com/61595808/111067755-ae798780-84d6-11eb-849c-035b23cc871b.png)
*Modelin her evrişim katmanı çıkışında farklı ağırlıklara sahip filtreler hesaplanır ve katman sayısı artıkça filtrelerde oluşan öznitelikler görüntünün ‘derinliklerini’ simgelemektedir.

![image](https://user-images.githubusercontent.com/61595808/111067768-b9ccb300-84d6-11eb-87d6-659b767a27fe.png)

![image](https://user-images.githubusercontent.com/61595808/111067772-c05b2a80-84d6-11eb-8664-1625709f3ed3.png)

![image](https://user-images.githubusercontent.com/61595808/111067775-c4874800-84d6-11eb-9460-3e18050fc120.png)

Şimdi ise Anaconda'da kullandığım kısımları göstereceğim.
![image](https://user-images.githubusercontent.com/61595808/111067891-6870f380-84d7-11eb-9720-5d34b6416966.png)

![image](https://user-images.githubusercontent.com/61595808/111067901-6f980180-84d7-11eb-9342-13b5ce4b6c75.png)

Bir çok kitabı seçip onlar için sonuçlar:
![image](https://user-images.githubusercontent.com/61595808/111067935-92c2b100-84d7-11eb-8704-c7e52f5a29a9.png)
![image](https://user-images.githubusercontent.com/61595808/111067940-9c4c1900-84d7-11eb-904c-aa9cf7483507.png)
![image](https://user-images.githubusercontent.com/61595808/111067953-b2f27000-84d7-11eb-99d0-5b33b777489d.png)
![image](https://user-images.githubusercontent.com/61595808/111067964-ba197e00-84d7-11eb-90b7-993dcadee512.png)
![image](https://user-images.githubusercontent.com/61595808/111067970-c7cf0380-84d7-11eb-923e-543c641c6986.png)
![image](https://user-images.githubusercontent.com/61595808/111067974-cdc4e480-84d7-11eb-942f-077c90e32b5f.png)
![image](https://user-images.githubusercontent.com/61595808/111067981-d5848900-84d7-11eb-80b4-93ef7413d4fa.png)
![image](https://user-images.githubusercontent.com/61595808/111067987-da493d00-84d7-11eb-8269-2d4b953f79bf.png)
![image](https://user-images.githubusercontent.com/61595808/111067995-e208e180-84d7-11eb-8d94-d48334258a1e.png)
![image](https://user-images.githubusercontent.com/61595808/111068001-e9c88600-84d7-11eb-84e0-60db8ccca59a.png)
![image](https://user-images.githubusercontent.com/61595808/111068003-edf4a380-84d7-11eb-907f-06aff91b1cc6.png)
![image](https://user-images.githubusercontent.com/61595808/111068007-f0ef9400-84d7-11eb-8067-a4541bbfb557.png)
![image](https://user-images.githubusercontent.com/61595808/111068009-f4831b00-84d7-11eb-8560-06ebd8e98ad6.png)
![image](https://user-images.githubusercontent.com/61595808/111068019-f8af3880-84d7-11eb-9b06-584bc5f3ddd6.png)
![image](https://user-images.githubusercontent.com/61595808/111068020-fbaa2900-84d7-11eb-8639-bb67b4ff5465.png)
![image](https://user-images.githubusercontent.com/61595808/111068023-ffd64680-84d7-11eb-8f59-bb88d3818714.png)
![image](https://user-images.githubusercontent.com/61595808/111068028-04026400-84d8-11eb-9b3b-36ea5a095101.png)
![image](https://user-images.githubusercontent.com/61595808/111068031-0795eb00-84d8-11eb-83f5-936e7a4560ac.png)
![image](https://user-images.githubusercontent.com/61595808/111068033-0b297200-84d8-11eb-9c81-724442fcd221.png)
![image](https://user-images.githubusercontent.com/61595808/111068038-1086bc80-84d8-11eb-96ae-c29ff1e812cc.png)
![image](https://user-images.githubusercontent.com/61595808/111068043-17153400-84d8-11eb-9699-754cdb7b8cc6.png)
![image](https://user-images.githubusercontent.com/61595808/111068050-1bd9e800-84d8-11eb-8299-d6c4498deb3a.png)
![image](https://user-images.githubusercontent.com/61595808/111068056-1f6d6f00-84d8-11eb-909a-9a625889cddf.png)
![image](https://user-images.githubusercontent.com/61595808/111068060-23998c80-84d8-11eb-90c9-730bef6f70f3.png)
![image](https://user-images.githubusercontent.com/61595808/111068063-26947d00-84d8-11eb-8cf3-75526d8bb2f1.png)
Genel anlamda hep book_jacket=kitap kapağı sonucunu verdi.Bu sonucu veren kitaplar:
book_jacket (34.64%)->Roman_22,24,25,26,28,29,30,32,35,43,45,47
Diğer sayfada ki hepsi Bookjacket
Kitaplarda daha çok doğruluk payı var kolyeye göre
Roman12->birdhouse (28.56%),Roman2->menu (68.56%),
Roman4->envelope (20.85%),Roman8->jersey (14.40%)
![image](https://user-images.githubusercontent.com/61595808/111068083-4d52b380-84d8-11eb-95be-81db770aba1f.png)
Şimdi ise kolye deki sonuçlara:
![image](https://user-images.githubusercontent.com/61595808/111068090-580d4880-84d8-11eb-8096-3b6be8b1d586.png)
![image](https://user-images.githubusercontent.com/61595808/111068091-5c396600-84d8-11eb-9f70-ae7be7807aad.png)
![image](https://user-images.githubusercontent.com/61595808/111068097-60658380-84d8-11eb-976b-5d26722921f4.png)
![image](https://user-images.githubusercontent.com/61595808/111068100-6491a100-84d8-11eb-94d8-e079e32aa1a6.png)
![image](https://user-images.githubusercontent.com/61595808/111068103-68bdbe80-84d8-11eb-8d3d-3099233d2f16.png)
![image](https://user-images.githubusercontent.com/61595808/111068108-6eb39f80-84d8-11eb-89ad-6975e25c5849.png)
![image](https://user-images.githubusercontent.com/61595808/111068113-75421700-84d8-11eb-8c99-abe21bde198b.png)
Kolye2->necklace (88.90%),Kolye4->necklace (64.09%),
Kolye21->Christmas_stocking (19.99%),Kolye3->necklace (19.80%),
Kolye43->mousetrap (96.79%),Kolye9->necklace (26.76%),
Kolye46->bottlecap (38.42%),Kolye11->chain (18.55%),
Kolye50->necklace (49.38%),Kolye13->necklace (34.20%),
Kolye60->necklace (88.93%),Kolye16->necklace (50.40%),
Kolye25->necklace (99.78%),Kolye18->necklace (66.85%),
Kolye19->necklace (26.65%),Kolye24->necklace (59.11%),
Kolye25->necklace (99.78%),Kolye26->swing (29.33%),
Kolye28->necklace (94.87%),Kolye29->necklace (68.25%),
Kolye35->necklace (11.07%),Kolye37->necklace (84.67%),
Kolye39->safety_pin (25.51%),Kolye48->chime (13.93%),
Kolye53->necklace (33.63%),Kolye62->hook (38.43%),
Kolye67->necklace (14.01%),Kolye70->necklace (13.51%),
Kolye72->crane (52.64%),Kolye73->bow (43.87%),
Kolye74->lacewing (6.35%),Kolye79->necklace (34.06%),
Kolye88->necklace (97.52%),Kolye89->gong (20.13%),
Kolye91->necklace (69.83%)





Kaynakça:
https://www.slideshare.net/YusufKurt/derin-renme-nedir-akademik-biliim-2016-sunumu
https://www.researchgate.net/publication/335653174_Derin_ogrenme_yontemleri_kullanarak_ekin_ile_yabanci_otlarin_birbirinden_ayirt_edilmesi
https://www.youtube.com/watch?v=tezYIXeo4c4&list=LLcL288xeuXnGSx1QFw4Wuwg&index=2&t=0s
https://devhunteryz.wordpress.com/2018/07/28/transfer-ogrenimi-transfer-learning/
https://medium.com/novaresearchlab/%C3%B6%C4%9Frenme-aktar%C4%B1m%C4%B1-transfer-learning-c0b8126965c4
https://medium.com/@ayyucekizrak/deri%CC%87ne-daha-deri%CC%87ne-evri%C5%9Fimli-sinir-a%C4%9Flar%C4%B1-2813a2c8b2a9
