# Yapay Zeka + Web Uygulama Güvenliği
1. [AI + XSS](#ai-ile-xss-saldırı-tespiti)
2. [AI + SQL injection](#ai-ile-sql-injection-tespiti)

## AI ile XSS saldırı tespiti
### Daha Önceki Yapılanlar:

#### 2025- [Web ve API zafiyetlerine yönelik güvenlik stratejileri ile XSS saldırılarının makine öğrenmesi yöntemleriyle tespiti / Security strategies against web and API vulnerabilities with machine learning-based detection of XSS attacks](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=5NNqZKwwGohPh6_KCcfp-myt0P_QOT1jo-ozRpzUdNNROiYc4zz334CqvVir3lB0)
1. **Tezin Amacı Ne?**
Web Zaafiyetleriyle bu zaafiyetlerin çözüm yöntemleri incelenmiş. XSS zaafiyeti Makine öğrenmesi yöntemiyle önlenmeye çalışılmıştır.

3. **Hangi probleme çözüm sunmuşlar?**
OWASP TOP 10 zaafiyetlerine ve XSS saldırısına çözüm sunuyor.


4. **Tezin sırası ve hangi sırayla ne anlattığı?**
-  Tezin amacı ve Ne için yapıldığı
-  İlgili Çalışmalar
-  OWASP TOP TEN listelemiş ve açıklamış
-  OWASP TOP TEN in gerçek dünya üzerine riskleri bahsedilmiş.
-  WEB Güvenliği için genel koruma senaryolarından bahsedilmiş.
-  Güncel Web güvenliği Pentesti (Juice Shop üzerinden OWASP TOP TEN) 
-  Makine Öğrenmesi Yardımıyla XSS Tespiti

5. **Kullanmış oldukları veriler neler?** 

Kaggle Veriseti 13038  satırdan oluşan 0 lar payloadın güvenli 1 olması da payloadın zararlı olduğunu söylüyor.

[Cross site scripting XSS dataset for Deep learning](https://www.kaggle.com/datasets/syedsaqlainhussain/cross-site-scripting-xss-dataset-for-deep-learning)


7. **Hangi Teknikleri Kullanmışlar?**</br>
BoW ve TFIDF teknikleri kullanılarak metinsel ozellik çıkarılmıştır. Bu metinsel özelliklere de ADABOOST , DT, KNN, Lojistik Regresyon (Logistic Regression: LR), MLP, Gaussian, Naive Bayes (NB), RF ve SVM algoritmaları testiyle test yapılmıştır. Ayrıca XGBClassifier gibi deişik bir sınıflandırma da kullanılmış.


8. **Kullandıkları Çözüm Yöntemleri Neler?**
Veri Önişleme Yöntemi (NTLK) label ve sentence ayrımı yapılmış.
Metin Temsil Yöntemi : Bow ve TFIDF yöntemi kullanılmış
Öznitelik Seçimi Yöntemi: CC, CSFSUBNET, IG, GR,ONER
Birleşik Öznitelik Seçimi Yöntemi: Input: 𝐹𝑒𝑎𝑡𝑢𝑟𝑒𝑆𝑒𝑡𝑠 = [𝐶 𝑓 𝑠𝑆𝑢𝑏𝑠𝑒𝑡, 𝐶𝐶, 𝐼𝐺, 𝐺𝑅, 𝑂𝑛𝑒𝑅]
                                  Output: 𝐶𝑜𝑚𝑚𝑜𝑛𝐹𝑒𝑎𝑡𝑢𝑟𝑒�
   



10. **Ne kadar başarı elde etmişler?**</br>
%99 un üzerinde başarı elde ettikleri algoritmalar olmuş.



11. **Buldukları Çözümlerde Eksikleri Neler? Neleri Es Geçmişler?Ne yapmamışlar**</br>
Gerçek hayata uygulaması düşük kalmış. Train test verisinden pek detaylı bahsedilmemiş.


14. **Sonuç !!!**




#### 2024-[Siber güvenlikte XSS web saldırılarının yapay zekâ zemininde analiz edilmesi / In cyber security XSS web attacks analysis on the basis of artificial intelligence](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=LY6e5xGA7WWUpEdrBmEPLpyBMlCYqig77z7kaRWyf5I_eI2vqlQnxo_Ao67sScv4)

#### 2023-[XSS saldırılarının tespiti için web uygulama güvenlik duvarı (WAF) ve makine öğrenme teknikleri kullanan hibrit bir yaklaşım / A hybrid approach using web application firewall (WAF) and machine learning techniques to detect XSS attacks](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=j_Fjwp4JS4mk97Puqti8rkrMkEWZytAKdFc0BR2eFA8cDOF3mD9J1yIJa5_UgtV-)

#### 2022- [Web tabanlı uygulamalarda siteler arası betik çalıştırma (XSS) zafiyetinin denetlenmesi için öğrenen bir sistem geliştirilmesi](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=qVqOZFj2DwNmvdf1oGFYiDytP4ahCsAVi6MgaVZ9IIobZcmkb_aJlYgAENHL4dRy)

#### 2022- [Makine öğrenmesi algoritmaları kullanarak web hizmetlerinde XSS saldırı tespiti / XSS attack detection on web services using machine learning algorithms](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=kIrIdtdJ31bRgjb6fHvMUV_qhkjaqmmTYiq2twG9tAsBKT27y5eTe5vGPCAuRM5a)

#### 2020-[Detecting SQL injection and XSS patterns with machine learning techniques](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=wf-FPgY-5qjHEzEoOgvMs5wesS3OFRiuF-YnCbdWZMGJVaKvokrFB1mBdfWp59Yd)

#### 2014- [XSS ve CSRF saldırıları ve çözüm önerileri / XSS AND CSRF attacks and solutions](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=48XPj7KKQhKUgntkUiKO3Mn6s-4sjHQspodRnM8kX8bEthX2kIp2gooUDO0CRdoa)


## AI ile SQL injection tespiti
#### 2024- [SQL enjeksiyon zafiyeti incelemesi ve iki popüler açık kaynak yazılıma SQL enjeksiyon testi uygulanması](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=htlyhJG97gjBTPjAeWRhPtX5E8Hw7XTgIe1vyUza4gvcdTGnFyDFOg8RDWVughgn)


#### 2024- [Web uygulamalarında SQL injectıon zafiyetinin önlenmesi için açıklanabilir yapay zeka kullanımı](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=UjlM15wKZGQW6TLC0pvCt92zShPrTVkda38bGNPoFy5121t9R9kqiFymRpC0IBsm)


#### 2024-[Detection of malicious SQL injections using svm and KNN algorithms /](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=KMB79M3N7zK1UR2WYeRgQlzADkNhC_cGG--JWr7hipsqs-xrygGqWqk2ZD2VA-lA)


#### 2023-[Detection of SQL injection attacks /](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=nLNfCsWgUluh5T2iyudShkYaIN0Foam36YUEZTEE0jVJtbCTqWMkHk974pY7hmfV)

#### 2023- [SQL enjeksiyonu saldırılarının makine öğrenmesi ile tespiti ve korunma yöntemleri](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=S2eMu1TIwY_v4mYv58xAr2XocOyvrtob7EAfV6k2w8MaZyQsbWzmRTMF8JuYYoFy)

#### 2022- [Veriyükü üzerinden sql enjeksiyon zafiyetlerin belirlenmesi / Determining sql injection vulnerabilities through payload](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=RjZwH00oMG4iNa5Sgvlgg31488SBZ2Z-dARQgVFIg-k66avbMAgzAYOiMM0hPxdU)

#### 2020- [Detecting SQL injection and XSS patterns with machine learning techniques /](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=wf-FPgY-5qjHEzEoOgvMs5wesS3OFRiuF-YnCbdWZMGJVaKvokrFB1mBdfWp59Yd)

#### 2019- [A security comparison of Oracle, SQL Server and MySQL database management systems against SQL injection attack vulnerabilities / Oracle, SQL Server ve MySQL veritabanı yönetim sistemlerinin SQL enjeksiyon saldırılarına karşı güvenlik açıkları bakımından karşılaştırması](https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=npGs9H39x7G6401x51yqpOiWeLO0jaqPQIHZ_D4FQaVeXSFoOy8Yv1kaaq3BGKRV)


