# Logical View

## Diagram

```text
                +--------------------+
                |      Customer      |
                +--------------------+
                          |
                          v
                +--------------------+
                |   Web Interface    |
                +--------------------+
                          |
         --------------------------------------
         |                |                   |
         v                v                   v
+----------------+ +----------------+ +----------------+
| Login Module   | | Product Module | | Order Module   |
+----------------+ +----------------+ +----------------+
         |                |                   |
         --------------------------------------
                          |
                          v
                  +----------------+
                  |    Database    |
                  +----------------+
```

## Penjelasan

Logical View menggambarkan hubungan antar modul di dalam sistem.

Customer mengakses aplikasi melalui Web Interface. Selanjutnya permintaan diproses oleh Login Module, Product Module, maupun Order Module sesuai kebutuhan. Seluruh data akan disimpan pada Database.

## Kesimpulan

Dengan pemisahan modul seperti ini, sistem menjadi lebih mudah dipelihara dan dikembangkan.