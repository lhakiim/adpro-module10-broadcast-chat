# adpro-module10-broadcast-chat

### 2.1: Original code, and how it run
![alt text](images/original_code.png)
Ketika melakukan run satu server `cargo run --bin server` dan tiga client `cargo run --bin client` secara bersamaan server mendengarkan port 2000. Ketika pengiriman pesan oleh client, server akan menerima pensan tersebut dan baru kemudian pesan tersebut akan didistribusikan kepada seluruh client yang terhubung. Hal ini menunjukkan mekanisme broadcast, di mana satu pesan dikirim ke banyak penerima.