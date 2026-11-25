Stickman Duel (Bleach Edition)

Game duel stickman 1 lawan 1 bertema Bleach. Pilih senjata dan kostum, lalu lawan komputer atau teman dalam satu layar, dengan dua analog untuk dua pemain. Dibuat dengan HTML, CSS, dan JavaScript murni (Canvas), tanpa library dan tanpa proses build.

Main sekarang: https://muqorobin298-lab.github.io/Stickman-Bleach/

Portofolio: https://muqorobin298-lab.github.io/Robin_Dev/

Fitur
Dua mode: Vs Komputer (1 analog) dan Vs Pemain (2 analog, satu layar).
6 senjata dengan karakter berbeda: Pedang, Tombak, Kapak, Belati, Palu, dan Busur.
Kostum: 8 pilihan warna dan 6 aksesori (polos, topi, bandana, tanduk, mahkota, topeng).
Jurus spesial: gelombang energi yang ditembakkan ke lawan, dengan jeda isi ulang sekitar 5 detik.
Tangkis (block) untuk mengurangi damage serangan dari depan.
3 tingkat kesulitan komputer: Mudah, Sedang, Sulit.
Pilihan ronde: 1 ronde, terbaik dari 3, atau terbaik dari 5. Tiap ronde 60 detik.
6 arena bertema anime (Senja Karakura, Malam Bersalju, Hujan Sakura, Istana Es, Soul Society, BANKAI!) atau pilih Acak.
Kontrol sentuh (analog virtual + tombol) untuk HP dan tablet, serta kontrol keyboard untuk komputer.
Efek suara dibuat langsung lewat Web Audio API, jadi tidak perlu file audio.
Pilihan senjata, kostum, arena, dan kesulitan tersimpan otomatis di browser (localStorage).
Cara Bermain

Tujuannya menghabiskan HP lawan. Kalau waktu habis, pemain dengan HP lebih banyak memenangkan ronde. Kalau HP sama, ronde diulang.

Keyboard
Aksi	Vs Komputer	Pemain 1 (Vs Pemain)	Pemain 2 (Vs Pemain)
Jalan	A / D atau panah kiri/kanan	A / D	panah kiri/kanan
Lompat	W, panah atas, atau Spasi	W	panah atas
Tangkis	S atau panah bawah	S	panah bawah
Serang	F atau J	F	. (titik)
Spesial	G atau K	G	/ (garis miring)

Tekan M kapan saja saat bermain untuk menyalakan atau mematikan suara.

Layar sentuh
Analog: geser ke kiri/kanan untuk jalan, ke atas untuk lompat, ke bawah untuk tangkis.
Tombol Serang dan Spesial ada di samping tiap analog.
Di mode Vs Pemain, analog kiri milik Pemain 1 dan analog kanan milik Pemain 2. Layar HP sebaiknya dimiringkan (landscape).
Senjata
Senjata	Damage	Jangkauan	Kecepatan	Catatan
Pedang	Sedang	Sedang	Sedang	Seimbang, cocok untuk pemula
Tombak	Sedang	Jauh	Sedang	Menusuk dari jarak aman
Kapak	Tinggi	Sedang	Lambat	Tidak mudah goyah saat menebas
Belati	Rendah	Pendek	Sangat cepat	Serangan beruntun, gerak lincah
Palu	Sangat tinggi	Pendek	Sangat lambat	Pukulan terkuat, tidak mudah goyah
Busur	Sedang	Jarak jauh	Cepat	Menembakkan panah
Menjalankan di Komputer

Tidak perlu instalasi. Cukup:

Unduh atau clone repo ini.
Buka index.html di browser (Chrome, Edge, Firefox, atau Safari).

Font Anton dan Inter dimuat dari Google Fonts, jadi butuh internet. Tanpa internet, game tetap jalan dengan font cadangan.

Publikasi dengan GitHub Pages
Upload index.html dan README.md ke repo Stickman-Bleach.
Buka Settings → Pages.
Pada Source, pilih branch main dan folder / (root), lalu Save.
Tunggu 1-2 menit. Game bisa dibuka di https://<username>.github.io/Stickman-Bleach/.
Struktur Proyek
Stickman-Bleach/
├── index.html   # seluruh game (HTML, CSS, dan JavaScript dalam satu file)
└── README.md
Teknologi

HTML5, CSS3, JavaScript (ES6), Canvas 2D, Pointer Events (kontrol multi-sentuh), Web Audio API, dan localStorage.

Kustomisasi

Semua data game ada di bagian atas <script> pada index.html:

SENJATA: ubah damage, jangkauan, kecepatan, dan knockback tiap senjata.
LEVEL: atur kecerdasan komputer (agresif, kemampuan menangkis, dan lainnya).
WARNA dan AKS: tambah warna atau aksesori baru.
tema: ubah atau tambah arena beserta warna latarnya.
Pembuat

Dibuat oleh Muhammad Muqorrobin (Robin), web developer pemula, sebagai bagian dari portofolio bertema Bleach.

GitHub: https://github.com/muqorobin298-lab
