# Tic Tac Toe — Player vs CPU / 2 Player

Sebuah game **Tic Tac Toe** berbasis web yang dapat dimainkan di browser, mendukung mode **2 Player lokal** maupun **Player vs CPU**. Game ini dibuat menggunakan **HTML, CSS, dan JavaScript** dalam satu file, sehingga dapat langsung dijalankan tanpa setup tambahan.

---

## Fitur

- Mode **2 Player** (local) — X dan O bermain bergantian.
- Mode **Player vs CPU** — Player X melawan CPU yang menaruh tanda secara otomatis (AI random).
- Deteksi **pemenang** dan **seri**, dengan highlight pada kotak yang menang.
- **Skor total** untuk Player X dan O.
- Tombol **Reset Game** untuk memulai ulang papan.
- Tombol **Reset Score** untuk mengatur ulang skor.
- Desain responsif, menggunakan **Flexbox** dan font **Poppins**.
- Semua logika berada di sisi frontend, **tanpa backend**.

---

## Cara Menjalankan

1. **Download / Salin** file HTML (`tictactoe.html`).
2. **Buka** file tersebut menggunakan browser modern (Chrome, Edge, Firefox, Safari).
3. **Pilih mode permainan** pada dropdown:
   - `2 Player`: bermain bergantian di satu perangkat.
   - `Player vs CPU`: Player X melawan CPU (O).
4. **Klik kotak** untuk menaruh tanda.
5. Gunakan tombol:
   - **Reset Game** → mulai ulang papan.
   - **Reset Score** → reset skor total.

---

## Struktur File

Semuanya berada dalam **satu file HTML**:

- **HTML** → Struktur papan, tombol, skor, dan status.
- **CSS** → Styling papan, tombol, hover effect, responsive layout.
- **JavaScript** → Logika permainan, AI CPU, giliran pemain, skor, evaluasi kemenangan.

---

## Teknologi

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **Font Google Poppins**

---

## Catatan

- Skor tersimpan di memori browser (**tidak persist di server**). Refresh halaman **tidak menghapus skor**, kecuali tombol *Reset Score* ditekan.
- Mode CPU menggunakan **AI random**, belum memakai strategi optimal. Bisa dikembangkan menjadi **AI pintar** dengan algoritma Minimax.

---
