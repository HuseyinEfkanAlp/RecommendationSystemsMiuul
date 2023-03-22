# RecommendationSystemsMiuul
Tavsiye Sistemleri Dersi Projeler Ve Ders İçerikleri

## İçerik
1. **Birliktelik Kuralı Öğrenimi (Association Rule Learning):**
* Veri içerisindeki örüntüleri, ilişkileri bulmak için kullanılan kural tabanlı bir Makine Öğrenmesi tekniğidir.
* Apriori algoritması kullanılır Apriori Algoritması; Sepet analizi yöntemidir. Ürün birlikteliklerini ortaya çıkartmak için kullanılır.

2. **İçerik Temelli Filtreleme (Content Based Filtering):**
* Ürün içeriklerinin benzerlikleri üzerinden tavsiyeler geliştirir.
* Elimizdeki ürünün meta bilgileri üzerinden benzerlikler hesaplanır ve o ilgili ürüne **en benzer olan ürünler önerilir**

3. **İş Birlikçi Filtreleme(Collaborative Filtering):**

  Bu konuyu 3 ana başlıkta inceleyeceğiz

  **1.Item-Based Collaborative Filtering**

* Ürün Benzerliği üzerinden öneriler yapılır.
* !! İçeriksel bir benzerlik değil, beğenilme benzerliği
* Birbirleri arasında en yüksek korelasyona sahip ürün en benzer beğenilme alışkanlığına sahiptir

  **2.User-Based Collaborative Filtering**

* Kullanıcı (User) Benzerlikleri üzerinden öneriler yapılır.
* !! Beğenme alışkanlıkları birbirine benzer olan kullanıcıların bilgilerini kullanarak öneriler yapılır.

  **3.Model-Based Collaborative Filtering**
  
* Boşlukları (Kullanıcıların Puan vermediği) doldurmak için user'lar ve movie'lar için var olduğu varsayılan latennt feature'ların 
ağırlıkları var olan veri üzerinden bulunur ve bu ağırlıklar ile var olmayan gözlemler için tahmin yapılır.



**Bu konular hakkında Projeler ve Ders Notlarını Repo da Bulabililirsiniz Ancak İş Birlikçi Filtreleme Datasetleri boyutu büyük olduğundan yüklemedim.**
