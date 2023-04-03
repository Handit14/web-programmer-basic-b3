1. Judul Algoritma: Menentukan Nilai Mutu Mahasiswa

2. Input:

Nilai mahasiswa

3. Langkah Kalkulasi:

Baca nilai mahasiswa
Jika nilai lebih besar atau sama dengan 80 dan kurang dari atau sama dengan 100, maka nilai mutu adalah A
Jika nilai lebih besar atau sama dengan 70 dan kurang dari 80, maka nilai mutu adalah B
Jika nilai lebih besar atau sama dengan 60 dan kurang dari 70, maka nilai mutu adalah C
Jika nilai kurang dari 60, maka nilai mutu adalah D


4. logic
if (nilai >= 80 && nilai <= 100) {
  mutu = "A";
} else if (nilai >= 70 && nilai < 80) {
  mutu = "B";
} else if (nilai >= 60 && nilai < 70) {
  mutu = "C";
} else {
  mutu = "D";
}