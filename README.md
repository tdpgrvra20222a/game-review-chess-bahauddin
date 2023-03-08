# Game Review Chess | M. Bahauddin Alfan 6025221028

Mekanik Gim | Ruang
- 8X8 2D array ruang diskrit (posisi pion akan selalu dalam kotak yang exactly centered)
- Hint Langkah Ketika memencet salah satu buah yg akan digerakkan
- Tidak mungkin ada illegal move yang diperbolehkan (dalam chess.com)

Mekanik Gim | Objek
- Jalan buah catur (dengan masing-masing peran seperti king, queen, knight, bishop, rook, pawn.)
- Memakan buah catur jika tidak termasuk illegal move (Rule)

Mekanik Gim | Waktu
- Waktu permainan masing-masing pemain (Time)
- Jika di catur dunia, ketika n adalah waktu yang dibutuhkan gerak dan pencet jam catur dibawah 1 detik maka waktu pemain akan bertambah +n (untuk blitz game)
- Di chess.com tidak berlaku aturan tersebut (atau bisa diatur increment-nya), tapi diperbolehkan pre-move
- Hirarki waktunya nested time, baru masing-masing player punya waktu sendiri.
