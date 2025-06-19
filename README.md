Lütfen FreeRADIUS log dosyasının tam yolunu girin: C:\Users\Desktop\S3M\logs\wired_auth_ok.txt

📊 **FreeRADIUS Kapsamlı Log Analizi (Auth & Acct)**

+----+--------------+----------------+--------+-----------+-------------+-----------------+
|    |   request_id | request_type   | user   | status    | nas_ip      | nas_port_type   |
+====+==============+================+========+===========+=============+=================+
|  0 |            0 | Authentication | ucp    | Challenge | 10.34.10.15 | Ethernet        |
+----+--------------+----------------+--------+-----------+-------------+-----------------+
|  1 |            1 | Authentication | ucp    | Challenge | 10.34.10.15 | Ethernet        |
+----+--------------+----------------+--------+-----------+-------------+-----------------+
|  2 |            2 | Authentication | ucp    | Challenge | 10.34.10.15 | Ethernet        |
+----+--------------+----------------+--------+-----------+-------------+-----------------+
|  3 |            3 | Authentication | ucp    | Challenge | 10.34.10.15 | Ethernet        |
+----+--------------+----------------+--------+-----------+-------------+-----------------+
|  4 |            4 | Authentication | ucp    | Challenge | 10.34.10.15 | Ethernet        |
+----+--------------+----------------+--------+-----------+-------------+-----------------+
|  5 |            5 | Authentication | ucp    | Challenge | 10.34.10.15 | Ethernet        |
+----+--------------+----------------+--------+-----------+-------------+-----------------+
|  6 |            6 | Authentication | ucp    | Challenge | 10.34.10.15 | Ethernet        |
+----+--------------+----------------+--------+-----------+-------------+-----------------+
|  7 |            7 | Authentication | ucp    | Challenge | 10.34.10.15 | Ethernet        |
+----+--------------+----------------+--------+-----------+-------------+-----------------+
|  8 |            8 | Authentication | ucp    | Challenge | 10.34.10.15 | Ethernet        |
+----+--------------+----------------+--------+-----------+-------------+-----------------+
|  9 |            9 | Authentication | ucp    | Challenge | 10.34.10.15 | Ethernet        |
+----+--------------+----------------+--------+-----------+-------------+-----------------+
| 10 |           10 | Authentication | ucp    | Accept    | 10.34.10.15 | Ethernet        |
+----+--------------+----------------+--------+-----------+-------------+-----------------+
| 11 |           11 | Accounting     | ucp    | Start     | 10.34.10.15 | Ethernet        |
+----+--------------+----------------+--------+-----------+-------------+-----------------+

🔄 **Bağlantı Yaşam Döngüsü:**
  - İstek ID: 0 | Kullanıcı: ucp | Durum: Challenge
    Süreç: Access-Request -> Access-Challenge
  - İstek ID: 1 | Kullanıcı: ucp | Durum: Challenge
    Süreç: Access-Request -> Access-Challenge
  - İstek ID: 2 | Kullanıcı: ucp | Durum: Challenge
    Süreç: Access-Request -> Access-Challenge
  - İstek ID: 3 | Kullanıcı: ucp | Durum: Challenge
    Süreç: Access-Request -> Access-Challenge
  - İstek ID: 4 | Kullanıcı: ucp | Durum: Challenge
    Süreç: Access-Request -> Access-Challenge
  - İstek ID: 5 | Kullanıcı: ucp | Durum: Challenge
    Süreç: Access-Request -> Access-Challenge
  - İstek ID: 6 | Kullanıcı: ucp | Durum: Challenge
    Süreç: Access-Request -> Access-Challenge
  - İstek ID: 7 | Kullanıcı: ucp | Durum: Challenge
    Süreç: Access-Request -> Access-Challenge
  - İstek ID: 8 | Kullanıcı: ucp | Durum: Challenge
    Süreç: Access-Request -> Access-Challenge
  - İstek ID: 9 | Kullanıcı: ucp | Durum: Challenge
    Süreç: Access-Request -> Access-Challenge
  - İstek ID: 10 | Kullanıcı: ucp | Durum: Accept
    Süreç: Access-Request -> Access-Accept
  - İstek ID: 11 | Kullanıcı: ucp | Durum: Start
    Süreç: Accounting-Request -> Acct-Start

챌 **Access-Challenge Girdileri:**
  - (0) Sent Access-Challenge Id 198 from 10.34.10.5:1812 to 10.34.10.15:43266 length 85
  - (1) Sent Access-Challenge Id 199 from 10.34.10.5:1812 to 10.34.10.15:43266 length 1089
  - (2) Sent Access-Challenge Id 200 from 10.34.10.5:1812 to 10.34.10.15:43266 length 1085
  - (3) Sent Access-Challenge Id 201 from 10.34.10.5:1812 to 10.34.10.15:43266 length 1049
  - (4) Sent Access-Challenge Id 202 from 10.34.10.5:1812 to 10.34.10.15:43266 length 136
  - (5) Sent Access-Challenge Id 203 from 10.34.10.5:1812 to 10.34.10.15:43266 length 119
  - (6) Sent Access-Challenge Id 204 from 10.34.10.5:1812 to 10.34.10.15:43266 length 125
  - (7) Sent Access-Challenge Id 205 from 10.34.10.5:1812 to 10.34.10.15:43266 length 153
  - (8) Sent Access-Challenge Id 206 from 10.34.10.5:1812 to 10.34.10.15:43266 length 161
  - (9) Sent Access-Challenge Id 207 from 10.34.10.5:1812 to 10.34.10.15:43266 length 125
