# MU Online — Android Port (Season 6 Ep.3)


##TUR

MU Online S6 istemcisinin çalışan Android portu — cihazda native açılıyor, canlı bir
OpenMU sunucusuna bağlanıyor ve dokunmatik kontrollerle (sanal joystick, saldırı/skill/
pot butonları) baştan sona oynanabiliyor. **Geliştirme devam ediyor.**

## Performans

Gerçek orta-segment cihaz (Adreno 618):

| Sahne | FPS |
|------|----:|
| Login | ~130–150 |
| Karakter seçim | ~55 |
| Oyun içi (Lorencia) | ~55–68 |

Oyun içi kare maliyeti (ms/kare, temsili):

| Geçiş (pass) | ms |
|------|----:|
| Terrain | ~6 |
| Objects | ~3–11 * |
| Characters | ~1–5 * |
| UI | ~3 |

<sub>* sahne yoğunluğuna göre değişir (ekrandaki canavar / diğer oyuncu sayısı)</sub>

> Oyun içi FPS, ilk derlemelerdeki ~5–8'den ~55–68'ye çıktı — optimizasyon sürüyor.



## Videolar

Cihazda çalışan port — oynanış kayıtları:

| Video | Açıklama |
|------|------|
| [Genel Oynanış](https://youtu.be/B8FKNitGhw4) | Genel bakış — açılış, dünya, dokunmatik kontroller |
| [Karakter Oluşturma](https://youtu.be/eMSeaBtf_Nk) | Karakter oluşturma ekranı |
| [Castle Siege](https://youtu.be/EQS0jA3Cf2c) | Kale kuşatması etkinliği |
| [Blood Castle](https://youtu.be/FlSAAdrY92A) | Blood Castle etkinliği |
| [LandOfTrials](https://youtu.be/T8hNny38niU) | LandOfTrials Haritası |

## Sunucu & Teşekkür

Sunucu tarafında [**OpenMU**](https://github.com/MUnique/OpenMU) kullanıldı — açık kaynak
OpenMU ekibine teşekkürler. 🙏

https://github.com/MUnique/OpenMU



##ENG

# MU Online — Android Port (Season 6 Ep.3)

A working Android port of the MU Online S6 client — runs natively on device, connects to a
live OpenMU server, and is fully playable with on-screen touch controls (virtual joystick,
attack / skill / potion buttons). **Work in progress.**

## Performance

Real mid-range device (Adreno 618):

| Scene | FPS |
|------|----:|
| Login | ~130–150 |
| Character select | ~55 |
| In-game (Lorencia) | ~55–68 |

In-game frame cost (ms/frame, representative):

| Pass | ms |
|------|----:|
| Terrain | ~6 |
| Objects | ~3–11 * |
| Characters | ~1–5 * |
| UI | ~3 |

<sub>* depends on how busy the scene is (monsters / other players on screen)</sub>

> In-game frame rate keeps improving across builds — optimization is ongoing.

## Videos

The port running on a real device — gameplay recordings:

| Video | Description |
|------|------|
| [General Gameplay](https://youtu.be/B8FKNitGhw4) | Overview — startup, world, touch controls |
| [Create Character](https://youtu.be/eMSeaBtf_Nk) | Character creation screen |
| [Castle Siege](https://youtu.be/EQS0jA3Cf2c) | Castle Siege event |
| [Blood Castle](https://youtu.be/FlSAAdrY92A) | Blood Castle event |
| [LandOfTrials](https://youtu.be/T8hNny38niU) | LandOfTrials Map |

## Server & Credits

The server side runs on [**OpenMU**](https://github.com/MUnique/OpenMU) — an open-source
Thanks to the OpenMU team. 🙏
