# pemograman5-umb
🎮 Pendekatan Game: Zombie Survival 3D

Judul: Zombie Survival: Asylum
Genre: Survival Horror FPS
Platform: PC (Windows, macOS, Linux)
Engine: Unity 2022.3 (URP/Standard RP)

✅ Tujuan Utama Game
Bertahan hidup selama mungkin dari serangan zombie.
Menjelajahi lingkungan untuk mencari amunisi, health pack, dan item penting lainnya.
Dapatkan skor/XP dengan membunuh zombie.
🧠 Struktur Alur Game

1.⁠ ⁠Main Menu Scene
Tombol: Start Game, Options, Exit
Menyimpan konfigurasi resolusi, kontrol, audio.
2.⁠ ⁠Gameplay Scene (Asylum Night Map)
Player Controller:

FPS Controller (berjalan, berlari, membidik, menembak)
HUD menampilkan peluru tersisa dan ikon senjata
Flashlight (aktif di malam hari dengan radius pencahayaan terbatas)
Zombie AI:

Mendeteksi pemain dalam radius tertentu
Bergerak menuju pemain (pathfinding)
Menyerang jika dalam jarak serang
Mempunyai health dan efek saat terkena peluru
Lingkungan:

Peta outdoor malam hari dengan elemen:
Bus rusak
Windmill
Pickup Items (Ammo, Battery, Health)
Suasana gelap dan mencekam, didukung lighting dan efek suara
3.⁠ ⁠Sistem Senjata & Ammo
Script Weapon.cs menunjukkan sistem:
Tembakan dengan delay (canShoot)
ProcessRaycast() untuk deteksi tabrakan peluru
Animasi flash muzzle (muzzleFlash.Play())
Upgrade (Opsional):

Ganti senjata (pistol, shotgun, rifle)
Add headshot multiplier
4.⁠ ⁠Game Over State
Triggered saat player health = 0
Tampilan “YOU DIED” muncul
Opsi:
Play Again – Reload scene
Quit Game – Keluar aplikasi

Nama: chika priscila sanusi
nim : 210260041
link package
