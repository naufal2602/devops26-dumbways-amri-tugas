## Request Flow Architecture

<img width="857" height="693" alt="image" src="https://github.com/user-attachments/assets/c03f7bc6-7d45-49a2-a764-9ef543aa0fde" />

1. Client mengirimkan request.
2. Request diterima oleh **Reverse Proxy Server**.
3. Reverse Proxy meneruskan request ke **Web Server**.
4. Web Server meneruskan request ke **Application**.
5. Application menerima dan memproses data request.
6. Selama proses berlangsung, application dapat mengakses atau mengambil data dari **Database** jika diperlukan.
7. Setelah proses selesai, application mengirimkan output kembali ke **Web Server**.
8. Web Server meneruskan response ke **Reverse Proxy Server**.
9. Reverse Proxy Server mengirimkan response akhir kepada client.

## Reverse Proxy Function

**Reverse Proxy Server** berfungsi sebagai perantara antara client dan server melalui jaringan (internet). Reverse proxy menerima request dari client, kemudian meneruskannya ke server tujuan dan mengembalikan response kepada client.
