# Sistem Tasarımı

## Donanım
- Arduino Nano
- YL-69 toprak nem sensörü
- 12V DC elektrovana
- HC-05 Bluetooth modülü

## Yazılım Akışı
1. Sensör verisi okunur.
2. Eğer nem %30'un altındaysa, sulama başlatılır.
3. Bluetooth ile mobil uygulamadan manuel tetikleme yapılabilir.

## Veri Akışı
- Sensör ➔ Arduino ➔ Bluetooth ➔ Mobil cihaz
