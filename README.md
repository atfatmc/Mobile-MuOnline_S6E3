# MU Online — Android Port (Season 6 Ep.3)

MU Online S6 istemcisinin çalışan Android portu — cihazda native açılıyor, canlı bir
OpenMU sunucusuna bağlanıyor ve dokunmatik kontrollerle (sanal joystick, saldırı/skill/
pot butonları) baştan sona oynanabiliyor. **Geliştirme devam ediyor.**

## Görseller / Video
<!-- kendi ekran görüntülerini / videonu buraya ekle -->
|  |  |
|--|--|
| ![](Debug_01.jpeg) | ![](Debug_03.jpeg) |
| ![](Debug_08.jpeg) | ![](Debug_09.jpeg) |

🎥 Oynanış videosu: <link>

## Performans

Gerçek orta-segment cihaz (Adreno 618):

| Sahne | FPS |
|------|----:|
| Login | ~130–150 |
| Karakter seçim | ~50 |
| Oyun içi (Lorencia) | ~45–50 |

Oyun içi kare maliyeti (ms/kare, temsili):

| Geçiş (pass) | ms |
|------|----:|
| Terrain | ~6 |
| Objects | ~3–11 * |
| Characters | ~1–5 * |
| UI | ~3 |

<sub>* sahne yoğunluğuna göre değişir (ekrandaki canavar / diğer oyuncu sayısı)</sub>

> Oyun içi FPS, ilk derlemelerdeki ~5–8'den ~30–50'ye çıktı — optimizasyon sürüyor.



## Sunucu & Teşekkür

Sunucu tarafında [**OpenMU**](https://github.com/MUnique/OpenMU) kullanıldı — açık kaynak
MU Online sunucu emülatörü. Bu portu test edip oynanabilir hale getiren altyapı için
OpenMU ekibine teşekkürler. 🙏

https://github.com/MUnique/OpenMU