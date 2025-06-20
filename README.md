![](https://ars.els-cdn.com/content/image/3-s2.0-B9780128130926000022-f01-02-9780128130926.jpg)
# Göz İzleyici (Eye Tracker)

**Göz İzleyici** projesi, Python ve OpenCV kullanarak göz hareketlerini gerçek zamanlı izleyen bir sistem sunar. Bu sistem, kullanıcıların ekrandaki öğelere baktıklarında göz hareketlerini izler ve kaydeder. Gelişmiş kullanıcı etkileşimi sağlamak amacıyla, bu yazılım göz izleme ve etkileşimli projelerde kullanılabilir.

## 🛠 Kullanılan Teknolojiler

* **Python 3.x**: Yazılımın temel dili.
* **OpenCV**: Görüntü işleme ve bilgisayarla görme kütüphanesi.
* **dlib**: Yüz tespiti ve göz takibi için kullanılan kütüphane.
* **NumPy**: Matematiksel işlemler için.
* **Matplotlib**: Sonuçları görselleştirmek için.

## 🚀 Başlarken

Projenin çalışabilmesi için bilgisayarınızda bazı araçları kurmanız gerekecek. Adımları takip ederek hızlıca kurulumu gerçekleştirebilirsiniz.

### 1. Gerekli Kütüphaneler

Projede kullanılan bağımlılıkları yüklemek için aşağıdaki komutu çalıştırın:

```bash
pip install -r requirements.txt
```

Eğer `requirements.txt` dosyanız yoksa, aşağıdaki kütüphaneleri manuel olarak yükleyebilirsiniz:

```bash
pip install opencv-python dlib numpy matplotlib
```

### 2. Projeyi Çalıştırma

1. **`eye_tracker.py`** dosyasını çalıştırarak yazılımı başlatın:

   ```bash
   python eye_tracker.py
   ```

2. Yazılım, bağlı kamerayı kullanarak göz hareketlerini izler. Ekranda gözlerinizin takibi ile ilgili anlık veriler gösterilecektir.


## 🔧 Kullanım

* Yazılım çalıştığında, ekrandaki öğelere odaklanarak göz hareketlerini izleyebilirsiniz.
* Gözlerinizin hareketi takip edilerek, kullanılan platformlarda veya oyunlarda farklı etkileşimler sağlanabilir.


* **Yüz Tanıma Entegrasyonu**: Kullanıcıların gözlerinin yanı sıra yüz ifadelerini de izleyerek daha kapsamlı bir analiz yapabilme.
* **Hareketli Göz İzleme**: Hareketli nesnelere odaklanarak göz izleme yeteneğini artırma.
* **Daha Fazla Platform Desteği**: Farklı platformlar ve cihazlarla entegrasyon sağlama.


