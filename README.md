# Advprog-modul10-BroadcastChat

Nama: Athallah Damar Jiwanto <br>
NPM: 2306245024 <br>
Kelas: Advprog-B
<hr>

## Experiment 2.1: Original code, and how it run
![experiment 2.1 commit1](images/images1.png)
Pada tahap ini, Saya menguji aplikasi chat WebSocket dengan satu server (port 2000) dan tiga client. Semua client dapat terhubung, bertukar pesan, dan menerima pesan secara serempak tanpa hambatan karena komunikasi berlangsung asynchronous. Setiap pesan yang dikirim oleh satu client langsung diteruskan ke client lain, membuktikan fitur broadcast berjalan lancar. Hasil ini memperlihatkan bahwa tokio_websockets dan channel broadcast dari tokio efektif untuk membangun chat real-time yang sederhana.