# **Rust Tutorial & Exercise**
**Muhammad Hilal Darul Fauzan**<br/>
**2206830542**<br/>
**Pemrograman Lanjut C**<br/>

## **Tutorial Modul 8: Software Architecture**

a. What is amqp?
- AMQP merupakan singkatan dari Advanced Message Queuing Protocol. AMQP adalah sebuah *open standard application layer protocol* yang difokuskan pada *message-oriented middleware*. Protokol ini memungkinkan aplikasi *client* untuk berkomunikasi dengan aplikasi sumber yang mengirimkan data serta menggunakan *messaging middleware* untuk menerima informasi yang dibutuhkan.

b. What it means? `guest:guest@localhost:5672` , what is the first guest, and what is the second guest, and what is `localhost:5672` is for? 
- String `guest:guest@localhost:5672` merupakan string koneksi untuk server AMQP. Dalam string ini, `guest:guest` adalah *username* dan *password* yang digunakan untuk autentikasi ke server, di mana dalam kasus ini *username* dan *password* keduanya adalah "guest". Selanjutnya, `localhost` menunjukkan hostname dari server, yang berarti server tersebut berjalan pada mesin yang sama dengan *client*. Lalu, `5672` adalah nomor port yang digunakan oleh server untuk mendengarkan permintaan dan merupakan port default untuk AMQP.