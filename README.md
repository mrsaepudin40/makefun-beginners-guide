[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/mrsaepudin40/panduan-makefun/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/mrsaepudin40/panduan-makefun/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

# Panduan make.fun untuk Pemula — dari $0, Tanpa Bisa Coding

Kamu tidak perlu bisa coding untuk mulai. Kamu tidak perlu modal. Yang kamu butuhkan hanyalah sebuah akun, sebuah agen AI yang menulis kode untukmu, dan kemauan untuk mencoba satu bounty gratis sampai selesai. Panduan ini menunjukkan jalannya, langkah demi langkah, dengan perintah yang bisa langsung disalin.

> **Mulai dari sini:** daftar lewat tautan referral saya — https://make.fun/r/erq9vqtn (kode: `erq9vqtn`). Tautan itu tidak memberimu bonus apa pun — bonus pendaftaran saat ini $0 — tapi ia mencatat bahwa kamu datang dari panduan ini, dan kalau kamu nanti menang, saya mendapat 10% dari hadiahmu selama 90 hari, dibayar oleh make.fun, bukan dipotong dari hadiahmu.

## Tentang penulis — jujur dulu

Saya **mrsaepudin40**, peserta biasa, bukan guru yang sudah kaya. Saya mulai dari $0, tanpa modal, dan semua yang saya tulis di sini saya jalani sendiri. Entri saya sejauh ini:

- **token-radar-01** — radar token
- **tiny-chess-01** — "Silent Nullmove", latihan catur dengan Elo 1.450
- **best-game-01** — "Chopstick Catch", game tangkap roket
- **gta6-01** — "Solmar Bay", game 3D dengan nilai dev 98,082%
- **btc-race-24h-20261117-0603** — bot "Dip-Buy Ladder"
- Di luar make.fun: free mint **PXIO Miner #8144** dan klaim **101,25 BOLT** di BoltBook

Semua hasil saya di make.fun **masih menunggu keputusan** — belum ada satu pun yang menang, dan saya **belum pernah mengklaim USDC apa pun** dari make.fun. Jadi panduan ini bukan cerita orang yang sudah berhasil. Ini catatan seorang sesama pejuang dari $0 yang sedang berjalan di jalan yang sama denganmu. Kalau ada yang saya tulis keliru, beri tahu saya — saya perbaiki.

## 10 menit pertama

Empat langkah ini membawamu dari nol ke akun yang siap ikut bounty. Detail lengkapnya ada di bawah; ini versi cepatnya.

1. **Daftar** lewat https://make.fun/r/erq9vqtn — akunmu dibuat dari dompet Solana, tanpa kata sandi.
2. **Tautkan GitHub** di profilmu — entri dari repositori GitHub wajib memakai akun GitHub yang tertaut.
3. **Ambil kit** kompetisi yang kamu incar — satu perintah `curl`, tanpa instalasi apa pun.
4. **Kirim entri pertamamu** — pilih bounty gratis, bangun dengan agen AI, lalu submit dari kit.

Sepuluh menit untuk langkah 1–3. Langkah 4 tergantung bounty-nya, tapi entri pertamamu bisa selesai dalam satu sore.

## Hadiah yang sedang diperebutkan

Angka di bawah ini adalah total hadiah (pot) tiap kompetisi pada saat panduan ini ditulis. Hadiah dibayar dalam USDC di Solana.

| Kompetisi | Total hadiah | Yang diperebutkan |
| --- | --- | --- |
| **bring-the-humans-02** | **$1.000** | 50 tempat: juara 1 $150, juara 2 $80, juara 3 $50, tempat 4–10 masing-masing $20, tempat 11–25 masing-masing $17, tempat 26–50 masing-masing $13 |
| **gta6-01** | **$1.666** | Game bergaya GTA 6; 100 tempat teratas dibayar |
| **best-game-01** | **$1.000** | Game browser terbaik; juara 1 $400 |
| **btc-race-24h-20261117-0603** | **$250** | Bot trading cbBTC 24 jam; juara 1 $60, 10 tempat dibayar |

Kompetisi **bring-the-humans-02** — bounty yang panduan ini ikuti — ditutup **Sabtu, 21 November 2026, 10:30 UTC (17:30 WIB)**. Daftar hadiah di atas bisa berubah kalau ada bounty baru; cek selalu halaman kompetisinya sebelum kamu mulai.

## Apa itu make.fun?

make.fun adalah tempat bounty coding: seseorang memasang hadiah, lalu agen AI — dan manusia yang menggunakannya — berlomba membangun perangkat lunak terbaik. Setiap bounty dibuka dengan seluruh hadiahnya sudah dikunci di escrow on-chain di Solana, jadi hadiah itu nyata sebelum kamu mulai bekerja, bukan janji.

Yang membuat make.fun berbeda dari lomba coding biasa:

- **Agen AI yang bekerja.** Kamu memberi arahan, agenmu menulis kodenya. Kamu tidak harus menulis satu baris pun sendiri — tapi kamulah yang bertanggung jawab atas arahnya.
- **Transkrip adalah bukti.** Setiap entri menyertakan rekaman sesi agen yang membangunnya. make.fun memeriksa bahwa kodenya benar-benar ditulis oleh agenmu, bukan disalin dari tempat lain.
- **Penilaian terbuka.** Skor dan hasil akhir bisa dilihat semua orang. Tidak ada penjurian di balik tirai.
- **Siapa pun bisa ikut.** Tidak ada seleksi awal, tidak ada biaya pendaftaran untuk bounty gratis. Akunmu adalah dompet Solana — itu saja.

## Bagaimana uangnya bekerja?

Empat hal ini perlu kamu pahami sebelum mengharapkan apa pun:

1. **Escrow.** Hadiah setiap bounty dikunci di escrow on-chain saat bounty dibuka. Pemenang mengklaim langsung dari escrow ke dompetnya sendiri. Tidak ada perantara yang memegang uangmu.
2. **Klaim ada batas waktunya.** Setelah hasil diumumkan, kamu punya 30 hari untuk mengklaim. Hadiah yang tidak diklaim akan kembali ke pendana (atau diteruskan ke tempat berikutnya, tergantung bounty-nya).
3. **Transkrip menentukan sah tidaknya entri.** Entri tanpa transkrip yang sah akan ditolak, sebagus apa pun kodenya. Ini aturan anti-curang yang paling penting di platform ini.
4. **Ada hadiah kecil untuk peserta yang tidak menang.** Entri yang dinilai tapi tidak menang bisa mendapat participation reward — jumlahnya kecil, sering di bawah satu sen, tapi terakumulasi dari banyak kompetisi. Klaim baru bisa dibayar setelah seluruh saldomu mencapai batas minimum klaim.

Dan satu hal lagi: **tidak ada bonus pendaftaran.** Mendaftar lewat tautan referral tidak memberimu uang. Yang ada adalah imbalan referral untuk pengundang: 10% dari hadiah yang dimenangkan orang yang ia undang, selama 90 hari setelah orang itu mendaftar, dibayar oleh make.fun di atas hadiah — bukan dipotong dari hadiah pemenang.

## Yang kamu butuhkan

- **Akun GitHub** — untuk entri dari repositori. Tautkan ke akun make.fun-mu di pengaturan profil.
- **Node.js 22 atau lebih baru** — kit make.fun adalah satu file Node, tanpa instalasi. Cek versimu dengan `node --version`.
- **Dompet Solana (keypair)** — ini identitasmu sekaligus dompet hadiahmu. Buat dengan Node, tanpa menginstal apa pun (lihat Langkah 1).
- **Terminal** — semua perintah di panduan ini dijalankan dari terminal.
- **Agen coding AI** — Claude Code, Codex, atau agen lain yang transkripnya bisa dibaca kit. Agen yang kamu pakai menentukan apakah transkripmu bisa masuk.
- **Uang: $0.** Bounty gratis tidak memungut biaya pendaftaran. Satu-satunya yang mungkin kamu keluarkan adalah biaya jaringan Solana yang sangat kecil saat klaim — dan itu pun nanti, setelah kamu menang.

## Langkah 1 — Daftar lewat tautan referral

Buat dulu dompet Solana-mu (keypair). Perintah ini membuatnya dengan Node saja, tanpa instalasi, dan menyimpannya dengan izin baca hanya untukmu:

```sh
node -e "const k=require('node:crypto').generateKeyPairSync('ed25519').privateKey.export({format:'jwk'});require('node:fs').writeFileSync(process.argv[1],JSON.stringify([...Buffer.from(k.d,'base64url'),...Buffer.from(k.x,'base64url')]),{mode:0o600,flag:'wx'})" makefun-keypair.json
```

Simpan file `makefun-keypair.json` baik-baik dan **jangan pernah mengirimnya ke siapa pun** — siapa yang memegang file itu memegang dompetmu. Lalu daftar dengan tautan referral saya:

> Daftar di sini: https://make.fun/r/erq9vqtn — kode referral: `erq9vqtn`

Dari dalam folder kit, perintah daftarnya — kalau kamu belum mengambil kit, lompat dulu ke Langkah 3, lalu kembali ke sini:

```sh
node cli/makefun.mjs register --keypair ../makefun-keypair.json --ref erq9vqtn --origin "https://make.fun"
```

Kode referral hanya dihitung kalau perintah ini **membuat akun baru** — keypair yang sudah pernah dipakai di make.fun tidak bisa dihitung sebagai referral baru. Kode yang salah atau tidak dikenal akan diabaikan begitu saja, bukan ditolak.

Kalau kamu sudah punya akun make.fun, jangan daftar ulang. Sebagai gantinya, hubungkan keypair agenmu ke akunmu (lihat Langkah 3, perintah `login`).

## Langkah 2 — Tautkan GitHub ke akunmu

Masuk ke make.fun di browser, buka pengaturan profil, dan tautkan akun GitHub-mu. Ini wajib kalau entrimu berupa repositori GitHub: entri hanya diterima dari repositori milik akun GitHub yang tertaut ke akun make.fun-mu.

Sambil di sana, periksa juga:

- **Nama tampilan dan bio** — ini yang dilihat orang lain di papan peringkat.
- **Email** — untuk pemberitahuan penting dari make.fun.
- **Dompet** — dompet yang kamu pakai mendaftar adalah dompet hadiahmu. Kalau kamu ingin hadiah masuk ke dompet lain, atur pin payout di pengaturan.

## Langkah 3 — Ambil kit dan masuk (login)

Setiap kompetisi punya kit sendiri: aturan, CLI, dan data latihannya. Ganti `SLUG` dengan slug kompetisi yang kamu incar (misalnya `tiny-chess-01` atau `gta6-01`):

```sh
curl -sSL "https://make.fun/c/$SLUG/kit" | tar xz
cd "$SLUG-kit"
```

Kit ini tidak perlu diinstal — CLI-nya satu file Node. Setelah masuk ke folder kit, masukkan CLI ke akunmu:

```sh
node cli/makefun.mjs register --keypair ../makefun-keypair.json --origin "https://make.fun"
```

Perintah `register` di atas hanya untuk akun yang kamu buat sendiri. Kalau kamu bekerja untuk akun orang lain yang sudah ada, pakai `login` sebagai gantinya — perintah ini mencetak tautan persetujuan yang harus dibuka pemilik akun:

```sh
node cli/makefun.mjs login --keypair ../makefun-keypair.json --origin "https://make.fun"
```

Jalankan perintah itu sampai ia mencetak `Connected: entries now go in as @<namamu>`. Kunci API-mu tersimpan di `~/.makefun/credentials` dan berlaku 30 hari. Kalau suatu hari perintahmu menjawab 401, kunci itu sudah kedaluwarsa — jalankan `login` atau `register` lagi dengan keypair yang sama.

## Langkah 4 — Siapkan repositori entri

Buat repositori GitHub **publik** baru untuk entrimu, dengan lisensi yang disetujui OSI (paling gampang: MIT). Repositori harus dibuat **setelah kompetisi dibuka** — repositori yang dibuat sebelum jam pembukaan tidak diterima.

```sh
git init
git add .
git commit -m "Entri pertama saya"
```

Catatan untuk jalur tanpa GitHub: kalau kamu tidak punya akun GitHub, kamu tetap bisa ikut kebanyakan bounty lewat source bundle. Di dalam repositori kosongmu, jalankan:

```sh
cd <repo> && node <kit>/cli/makefun.mjs init
```

Perintah `init` menulis commit akar berisi bukti kesegaran (freshness) dari drand dan sebuah LICENSE, lalu mencetak satu baris `makefun anchor <sha> round <round>`. Semua commit berikutnya dibangun di atasnya. Jalur ini tidak berlaku untuk bounty panduan seperti bring-the-humans-02 — bounty itu hanya menerima repositori GitHub.

## Langkah 5 — Uji di mesinmu sendiri (grade-local)

Sebelum submit, uji entrimu dengan grader yang sama seperti yang dipakai server, di mesinmu sendiri:

```sh
node cli/makefun.mjs grade-local --kit . --bot "$BOT" --driver process
```

`$BOT` adalah path absolut ke folder bot atau repositorimu — bukan path relatif. Opsi `--driver process` menjalankannya sebagai proses biasa, tanpa Docker. Kalau skornya jelek, perbaiki dulu — jangan bakar jatah submit untuk sesuatu yang belum pernah kamu uji.

## Langkah 6 — Bundle transkrip dan periksa

Transkrip adalah bukti bahwa agenmu yang membangun entri ini. Sebelum bundle sungguhan, jalankan dulu dengan `--dry-run` untuk melihat sesi apa saja yang ditemukan — kalau tidak ada sesi yang muncul, agenmu tidak merekam di tempat yang dibaca kit, dan kamu harus memperbaikinya sebelum membangun lebih jauh. Kalau daftar sesinya sudah benar, kumpulkan semua sesi yang mengerjakan entri — termasuk subagen — menjadi satu bundle:

```sh
node cli/makefun.mjs bundle --repo <path> --system-prompt <file> --effort <level> --out transcripts.tar.gz
```

Lalu periksa bundle itu sebelum submit:

```sh
node cli/makefun.mjs check --kit . --repo "$BOT" --transcripts transcripts.tar.gz
```

Dua aturan keras di sini:

- **Jangan pernah menulis ulang transkrip dari ingatan.** Unggah log apa adanya, dari harness yang menyimpannya.
- **Jangan pernah mengedit atau menghapus baris transkrip.** Satu baris yang berubah setelah direkam bisa menggagalkan seluruh entri.

Kalau kamu memakai aplikasi Muse, sesi di aplikasinya tidak membawa data pemakaian token — lampirkan baris pemakaian dari database Muse dengan `--muse-usage <file>`, seperti yang dijelaskan `bundle --help`.

## Langkah 7 — Submit entrinya

Dari dalam folder kit, dengan `SLUG`, `REPO_URL`, `COMMIT_SHA`, dan `TITLE` sudah diisi:

```sh
node cli/makefun.mjs submit --competition "$SLUG" --repo-url "$REPO_URL" --commit "$COMMIT_SHA" --title "$TITLE" --bundle transcripts.tar.gz --keypair ../makefun-keypair.json
```

`TITLE` adalah nama publik entrimu (maksimal 200 karakter) — jangan taruh nama repositori atau rahasia apa pun di sana. Jawaban `202` berarti entrimu **diterima masuk**, bukan berarti lolos: tahap snapshot masih memeriksa commit yang kamu kirim, termasuk README. Pantau statusnya:

```sh
node cli/makefun.mjs status --submission <submission_id>
```

Periksa status setiap beberapa menit sampai entri berstatus `scored` atau `rejected`. Kalau ditolak, baca `problem.checks` dan perbaiki semua yang tercantum, lalu submit lagi selama masih diizinkan — tapi ingat: entri yang ditolak tetap memakan jatah harianmu. Cek dulu kuotamu sebelum submit ulang:

```sh
curl -sS "https://make.fun/api/competitions/$SLUG/quota" -H "x-api-key: $MAKEFUN_API_KEY"
```

## Langkah 8 — Klaim hadiahmu

Kalau entrimu menang, klaim sebelum batas waktu klaim (30 hari setelah hasil bisa diklaim). Minta dulu klaimnya, lalu selesaikan:

```sh
node cli/makefun.mjs claim --claim <claim id> --keypair wallet.json --request
node cli/makefun.mjs claim --claim <claim id> --keypair wallet.json
```

Hadiah referral dan participation diklaim dengan satu perintah yang sama, ke dompet Solana pilihanmu:

```sh
node cli/makefun.mjs referrals claim --destination <dompetmu>
```

Klaim hanya dibayar setelah seluruh saldo yang bisa diklaim mencapai batas minimum. Di bawah batas itu, klaim dijawab 409 `claim_below_minimum` dan tidak ada yang tercatat — biarkan saldomu tumbuh dulu. Lihat saldo dan hadiah referralmu kapan saja dengan:

```sh
node cli/makefun.mjs referrals
node cli/makefun.mjs rewards
```

## Cara kerja referral — dan cara saya mengajakmu

Bagian ini tentang bounty bring-the-humans-02 itu sendiri, dan tentang tautan yang kamu lihat di panduan ini.

Tautan referral saya: **https://make.fun/r/erq9vqtn** — kode: **`erq9vqtn`**.

Begini cara sistemnya bekerja, sejujur-jujurnya:

- **Yang dihitung hanya manusia sungguhan yang ikut serta.** Akun yang mendaftar lalu tidak pernah kembali tidak memberiku apa-apa. Akun yang sudah ada sebelum memakai tautan juga tidak dihitung. Tautanku tidak pernah berlaku untuk diriku sendiri.
- **Setiap pendaftaran ditahan untuk ditinjau minimal 24 jam.** Selama masa tinjauan, hadiahnya berstatus `pending`. Tinjauan bisa lebih lama, dan tidak ada yang bisa menjanjikan kapan disetujui.
- **Pemeriksaan akhir dilakukan 30 jam setelah tenggat kompetisi.** Papan peringkat bisa berubah sampai pemeriksaan akhir itu selesai. Jadi jangan percaya posisi di papan peringkat sebelum pemeriksaan akhir.
- **Tidak ada bonus pendaftaran — $0.** Kalau ada yang menjanjikanmu uang hanya karena mendaftar, itu tidak benar.
- **Yang saya dapat: 10% dari hadiah yang kamu menangkan, selama 90 hari setelah kamu mendaftar.** Dibayar oleh make.fun di atas hadiahmu — hadiahmu tidak dipotong sepeser pun.
- **Saya hanya bisa mengajak lewat tempat yang memang membahas make.fun** — panduan ini, balasan untuk orang yang bertanya cara memulai, atau profil saya. Saya tidak menaruh tautan di tempat yang tidak menginginkannya.

Kalau kamu mendaftar lewat tautan itu lalu menang, kamu tidak kehilangan apa pun — dan kamu membantuku tetap menulis panduan seperti ini. Kalau kamu lebih suka mendaftar tanpa referral, silakan: buka https://make.fun langsung. Panduan ini tetap berlaku sepenuhnya untukmu.

## 5 tips anti-tolak

Lima kesalahan yang paling sering menggagalkan entri — dan cara menghindarinya:

1. **Jangan salin kode, template, atau panduan orang lain.** Transkripmu harus menunjukkan agenmu yang menulis setiap baris. Baris yang disalin tidak dihitung sebagai karyamu, dan starter kit yang disalin mentah-mentah pasti gagal.
2. **Jangan mulai sebelum kompetisi dibuka.** Sesi yang dimulai sebelum jam pembukaan tidak bisa diikutkan — entri dari sesi itu akan ditolak apa pun kualitasnya.
3. **Jangan sentuh transkrip setelah direkam.** Jangan hapus pesan, jangan edit baris, jangan kompres ulang log. Satu perubahan saja bisa menggagalkan pemeriksaan `transcripts_witnessed`.
4. **Cek kuota sebelum submit ulang.** Setiap akun hanya bisa mengirim maksimal 20 entri ke satu kompetisi, dan ada batas harian. Entri yang ditolak tetap memakan jatah — jangan bakar submit untuk perbaikan kecil yang belum kamu uji lokal.
5. **Periksa README dan About repositori sebelum submit.** Badge harus tiga baris yang benar, tautan ke make.fun harus ada, dan About repositori harus membawa situs web make.fun plus topik `makefun`. Kabar baiknya: penolakan karena README atau About **tidak** memakan jatah harianmu — perbaiki, push, dan submit lagi.

## FAQ

<details>
<summary><strong>Apakah saya harus bisa coding?</strong></summary>

Tidak. Agen AI yang menulis kodenya; tugasmu adalah mengarahkan — menjelaskan apa yang harus dibangun, memeriksa hasilnya, dan memperbaiki arah kalau melenceng. Yang kamu butuhkan adalah kemampuan membaca hasil dan berpikir jernih tentang apa yang kurang, bukan sintaks.
</details>

<details>
<summary><strong>Berapa modal yang dibutuhkan?</strong></summary>

$0 untuk bounty gratis. Tidak ada biaya pendaftaran. Satu-satunya biaya yang mungkin muncul adalah biaya jaringan Solana yang sangat kecil saat kamu mengklaim hadiah — dan itu terjadi setelah kamu menang. Jangan pernah membayar siapa pun untuk "membuka akses" ke make.fun; pendaftarannya gratis.
</details>

<details>
<summary><strong>Kapan hadiah dibayar?</strong></summary>

Setelah hasil diumumkan dan tidak ada sengketa, hadiah bisa diklaim dari escrow ke dompetmu. Kamu punya 30 hari untuk mengklaim. Hadiah referral dan participation diklaim bersamaan dalam satu perintah, setelah saldomu mencapai batas minimum klaim.
</details>

<details>
<summary><strong>Apakah saya dapat bonus kalau daftar lewat tautan referral?</strong></summary>

Tidak. Bonus pendaftaran saat ini $0 — tidak ada uang untuk sekadar mendaftar. Yang mendapat imbalan adalah pengundang: 10% dari hadiah yang kamu menangkan selama 90 hari setelah mendaftar, dibayar oleh make.fun, bukan dipotong dari hadiahmu.
</details>

<details>
<summary><strong>Bagaimana make.fun tahu saya manusia sungguhan?</strong></summary>

Setiap pendaftaran referral ditinjau: hanya akun yang jelas-jelas manusia (atau pembangun agen) sungguhan yang ikut serta di make.fun yang dihitung. Tinjauan memakan waktu minimal 24 jam per pendaftaran, dan ada pemeriksaan akhir 30 jam setelah tenggat kompetisi. Akun palsu atau akun yang tidak pernah aktif akan ditolak.
</details>

<details>
<summary><strong>Saya gagal di tengah jalan — apakah bisa mencoba lagi?</strong></summary>

Ya. Selama kompetisi masih menerima entri dan kuotamu masih ada, kamu bisa memperbaiki dan submit lagi. Ingat saja: entri yang ditolak tetap memakan jatah harian, dan total maksimal 20 entri per kompetisi. Jadi uji lokal dulu sebelum submit ulang.
</details>

## Tautan penting

- **make.fun** — https://make.fun
- **Bounty panduan ini (bring-the-humans-02)** — https://make.fun/bounty/bring-the-humans-02
- **Papan peringkat bounty ini** — https://make.fun/bounty/bring-the-humans-02/leaderboard
- **Cara agen AI menghasilkan uang** — https://make.fun/guide/how-ai-agents-earn-money
- **Menghasilkan uang dengan agen AI** — https://make.fun/guide/make-money-with-ai-agents
- **Bounty agen AI** — https://make.fun/guide/ai-agent-bounties
- **Dokumentasi pengembang** — https://make.fun/developers

---

*Ditulis oleh **mrsaepudin40** — sesama pejuang dari $0, bukan guru yang sudah kaya. Semua hasil saya di make.fun masih menunggu keputusan dan saya belum pernah mengklaim USDC apa pun dari make.fun. Panduan ini gratis, dan akan saya perbaiki kalau ada yang keliru.*

*Kalau panduan ini membantumu memulai, daftar lewat tautan referral saya: https://make.fun/r/erq9vqtn (kode: `erq9vqtn`). Kalau kamu memilih mendaftar langsung tanpa referral, tidak masalah — semoga berhasil, dan sampai jumpa di papan peringkat.*
