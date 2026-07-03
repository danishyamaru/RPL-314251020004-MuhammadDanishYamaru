# Physical View

## Diagram

```text
+-------------+
|   Client    |
+-------------+
       |
       v
+----------------+
|   Internet     |
+----------------+
       |
       v
+----------------+
|   Web Server   |
+----------------+
       |
       v
+----------------+
| Application    |
|    Server      |
+----------------+
       |
       +--------------------+
       |                    |
       v                    v
+---------------+    +------------------+
| MySQL Server  |    | Payment Gateway  |
+---------------+    +------------------+
```

## Penjelasan

Pengguna mengakses sistem melalui browser. Permintaan dikirim melalui internet menuju Web Server. Selanjutnya Application Server memproses permintaan dan berkomunikasi dengan Database maupun Payment Gateway.

## Infrastruktur

- Client
- Internet
- Web Server
- Application Server
- Database Server
- Payment Gateway

## Kesimpulan

Physical View menunjukkan bagaimana seluruh komponen fisik saling terhubung sehingga sistem dapat berjalan dengan baik.