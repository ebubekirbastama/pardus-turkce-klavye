🇹🇷 Türkçe Klavye Kısayolu 💻⌨️

Bu küçük araç, Pardus ve diğer Linux dağıtımlarında tek tıklama ile
klavye düzenini Türkçe (Q) yapmanı sağlar.
Özellikle birden fazla dil kullanan kullanıcılar için hızlı çözüm! ⚡

------------------------------------------------------------------------

🧩 Özellikler

✅ Tek tıklamayla çalışır<br>
✅ Terminal açmadan klavyeyi Türkçe yapar<br>
✅ Pardus, Debian, Ubuntu ve tüm Linux masaüstlerinde çalışır<br>
✅ Hafif (sadece 1 satır komut!)
<br>
------------------------------------------------------------------------

⚙️ Kurulum

1️⃣ Bu repodaki tr-klavye.desktop dosyasını indir<br>
2️⃣ Dosyayı Masaüstü’ne taşı<br>
3️⃣ Terminali aç ve çalıştırılabilir hale getir:<br>

    chmod +x ~/Masaüstü/tr-klavye.desktop

4️⃣ Masaüstündeki simgeye bir kere tıkla 🖱️<br>
👉 Klavyen artık Türkçe (Q)!<br>

------------------------------------------------------------------------

🧠 İpucu

İstersen benzer şekilde İngilizce klavye için de bir dosya
oluşturabilirsin:

    Exec=setxkbmap us
    Name=İngilizce Klavye

Ya da tek dosya içinde TR ↔ US geçişini otomatik yapan versiyon da
ekleyebilirsin 🔄

------------------------------------------------------------------------

📦 Dosya İçeriği

    [Desktop Entry]
    Type=Application
    Name=Türkçe Klavye
    Comment=Klavye düzenini Türkçe (Q) olarak ayarlar
    Exec=setxkbmap tr
    Icon=input-keyboard
    Terminal=false
    StartupNotify=false

------------------------------------------------------------------------

🧑‍💻 Geliştirici

👤 Ebubekir Bastama<br>
🗓️ 2025<br>
💬 Öneri, geliştirme veya katkı için PR gönderebilirsin!<br>

------------------------------------------------------------------------

📜 Lisans

Bu proje MIT Lisansı ile paylaşılmıştır.<br>
Özgürce kullanabilir, düzenleyebilir ve paylaşabilirsin. ❤️<br>

------------------------------------------------------------------------

⭐️ Faydalı olduysa bir yıldız bırakmayı unutma!
