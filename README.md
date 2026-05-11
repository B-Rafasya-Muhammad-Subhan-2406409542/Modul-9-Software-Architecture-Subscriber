## Tutorial 9: Event-Driven Architecture (Subscriber)

**a. What is amqp?**
AMQP (*Advanced Message Queuing Protocol*) adalah protokol jaringan standar terbuka di tingkat aplikasi yang dirancang khusus untuk *message-oriented middleware*. Protokol ini mengatur bagaimana pesan dikirimkan secara aman, andal, dan efisien antara berbagai sistem atau aplikasi melalui sebuah *message broker*.

**b. What does it mean? `guest:guest@localhost:5672`, what is the first guest, and what is the second guest, and what is localhost:5672 is for?**
String tersebut merupakan URL koneksi yang digunakan oleh aplikasi untuk terhubung ke dalam *message broker* (RabbitMQ). Rinciannya adalah sebagai berikut:
- `guest` pertama adalah *username* *default* untuk login ke RabbitMQ.
- `guest` kedua adalah *password* *default* untuk *username* tersebut.
- `localhost` menandakan bahwa server RabbitMQ berjalan di komputer lokal (mesin yang sama dengan yang menjalankan kode ini).
- `5672` adalah *port* *default* yang didengarkan (listen) oleh RabbitMQ untuk menerima koneksi jaringan berprotokol AMQP.