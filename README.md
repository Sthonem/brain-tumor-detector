# Beyin Tümörü Tanı Uygulaması 🧠

Bu MATLAB App Designer projesi, MRI görüntülerinden beyin tümörü olup olmadığını tespit etmek için bir CNN modeli kullanır.

## 🚀 Özellikler
- MRI görüntüsünü yükleme ve önizleme
- Gri görüntüyü RGB'ye çevirme
- 20 epoch'luk eğitilmiş CNN modeliyle sınıflandırma
- Sonucu kullanıcı arayüzünde görüntüleme

## 📁 Dosya İçeriği
- `BT_Detector.mlapp`: MATLAB uygulaması
- `brain_tumor_cnn_epoch20.mat`: Eğitilmiş model dosyası
- `example_images/`: Test görüntüleri (opsiyonel)

## 🛠️ Gereksinimler
- MATLAB R2021b veya üzeri
- Deep Learning Toolbox
- Image Processing Toolbox

## 👨‍💻 Nasıl Kullanılır?
1. MATLAB'da `BT_Detector.mlapp` dosyasını açın.
2. Uygulamayı çalıştırın (Run).
3. Bir MRI görüntüsü seçin.
4. “Sınıflandır” butonuna tıklayın.

## 🧠 Eğitim Verisi ve Model
Model, 128x128 boyutunda MRI görüntüleri ile eğitilmiş olup, %94.59 doğrulama ve %89.47 test doğruluğuna sahiptir.

## 📃 Lisans
MIT Lisansı
