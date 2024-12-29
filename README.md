# Turner Sendromu Tespiti 

Bu proje, Turner sendromu gibi kromozomal anormalliklerin tespiti için derin öğrenme tabanlı bir model geliştirmeyi hedeflemektedir. Turner sendromu, bir X kromozomunun eksik veya yapısal olarak anormal olduğu bir durumdur ve genellikle X0 kromozom yapısıyla ilişkili bir hastalıktır. Bu proje, XX, XY ve X0 kromozom türlerinin sentetik olarak oluşturulmuş görüntülerinden bir veri seti oluşturarak, geliştirilen derin öğrenme modelinin bu türleri sınıflandırmasını sağlamaktadır.

## Projenin Amaçları

- **Turner sendromu tespiti:** X0 kromozom yapısını tespit ederek Turner sendromunun tanısına yönelik bir temel oluşturmak.
- **Kromozom sınıflandırması:** XX, XY ve X0 kromozom türlerini doğru bir şekilde ayrıştırmak.
- **Sentetik veri seti oluşturma:** Modeli eğitmek için çeşitlilik içeren sentetik kromozom görüntüleri tasarlamak.
- **Derin öğrenme modeli:** Evrişimli sinir ağları (CNN) kullanarak görüntülerden öznitelik çıkarımı ve sınıflandırma yapmak.

## Teknolojiler ve Araçlar

- **Python**: Model geliştirme ve veri işlemleri.
- **TensorFlow/Keras**: Derin öğrenme modeli tasarımı ve eğitimi.
- **Pandas**: Veri seti manipülasyonu ve çalışması.
- **Matplotlib/Seaborn**: Veri görselleştirme.
- **Pillow**: Sentetik görüntü oluşturma.
- **Scikit-learn**: Performans değerlendirmesi ve metriğ hesaplama.

## Proje Yapısı

- `data/`: Sentetik veri setinin bulunduğu dizin.
- `models/`: Kaydedilen model ağırlıkları.
- `notebooks/`: Projeyi eğitmek ve değerlendirmek için kullanılan Jupyter Notebook dosyaları.
- `README.md`: Proje hakkında bilgiler.

## Veri Seti

Bu projede sentetik olarak XX, XY ve X0 kromozom görüntüleri oluşturulmuştur. Her bir sınıf için 300 adet görüntü üretilmiş ve veri seti çeşitlilik için veri artırma teknikleriyle desteklenmiştir.

## Model Mimarisi

Modelimiz, şu temel bileşenlerden oluşmaktadır:

1. **Evrişim Katmanları**: Kromozom görüntülerinden temel özniteliklerin çıkarılması.
2. **Havuzlama Katmanları**: Görüntünün boyutunu azaltarak modelin karmaşıklığının azaltılması.
3. **Yoğun Katmanlar**: Sınıflandırma işleminde kullanılır.
4. **Dropout ve Normalizasyon**: Aşırı öğrenmenin engellenmesi ve model genellemesinin geliştirilmesi.

## Sonuçlar

<img width="912" alt="image" src="https://github.com/user-attachments/assets/f6562a39-b511-4302-a8ed-7ad5e204626e" />
<img width="333" alt="image" src="https://github.com/user-attachments/assets/f894cbf0-c1c1-4c84-b0c2-ed5221f504d9" />
<img width="362" alt="image" src="https://github.com/user-attachments/assets/68b8648d-f213-41a2-b484-a1f205a92885" />


