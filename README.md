# DeepVision-Detector

Bu repo, TensorFlow Hub üzerindeki önceden eğitilmiş SSD MobileNet V2 modeli kullanılarak yazılmış temel bir nesne tespiti (object detection) betiğini içerir.

Model, karmaşık görüntülerdeki nesneleri tespit edip etraflarına sınır kutuları (bounding box) çizer ve doğruluk oranlarını hesaplar. Kod yapısı karmaşadan uzak ve olabildiğince sade tutulmuştur.

Özellikle otonom İHA (UAV/UCAV) sistemlerinde ve Nvidia Jetson gibi donanımlarda yüksek kare hızlarıyla gerçek zamanlı hedef tespiti yapabilmek için uygun, hafif bir mimari tercih edilmiştir. Bu kod, söz konusu otonom sistemler için bir test ve altyapı adımıdır.

Kullanılan Kütüphaneler:
- Python
- TensorFlow / TF Hub
- NumPy, Matplotlib, PIL
