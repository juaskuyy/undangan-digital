UNDANGAN SCROLL ANIMATION — Juaa & Rawr

Cara deploy:
1. Ekstrak ZIP.
2. Upload index.html, music.mp3, dan folder frames ke root repository GitHub.
3. Cloudflare Pages: framework preset None, build command kosong, output directory root.
4. Jangan upload index.html saja; folder frames dan music.mp3 wajib ikut.

Cara pakai:
- Sentuh pintu untuk membuka undangan dan memulai musik.
- Scroll halaman; urutan frame setiap adegan mengikuti posisi scroll, jadi bukan pemutar video.
- Tulisan/ornamen dalam adegan mengikuti rekaman Canva asli karena frame berasal dari klip yang dikirim.
- Efek ini mengubah adegan mengikuti scroll, bukan merekonstruksi setiap objek terpisah. Untuk animasi teks mandiri, aset transparan diperlukan.

Pembaruan kecepatan: durasi scroll per scene dipercepat; setiap scene sekarang berganti dalam jarak scroll yang lebih pendek (112svh/dvh, dari 145svh/dvh).

Pembaruan: tiap adegan dimulai dari frame yang lebih maju agar tulisan yang muncul bertahap di video referensi sudah lebih lengkap saat adegan pertama kali terlihat. Scroll tetap menggerakkan rangkaian frame hingga frame akhir.
