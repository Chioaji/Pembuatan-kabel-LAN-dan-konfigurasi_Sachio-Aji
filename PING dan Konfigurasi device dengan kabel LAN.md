Note: untuk melakukan percobaan ini karna kita menggunakan kabel LAN, wifi pada laptop kita harus di nonaktifkan terlebih dahulu


A. PING

   1. Untuk melakukan PING pada percobaan ini kita menggunakan kabel LAN yang terhubung dari laptop ke router melalui HUB, untuk cek Ping bisa di lakukan dengan cara

          ping @ipAddress
                           

      <img src="https://github.com/Chioaji/Pembuatan-kabel-LAN-dan-konfigurasi_Sachio-Aji/assets/126127582/843dd1ac-b228-45cf-8fce-3aba6eda5f90" width=50% height=50%>

Note: Apabila saat pengecekan yang muncul adalah "unreachable" maka terdapat masalah pada Jaringan.
      Apabila yang muncul "Request time out" maka kemungkinan ada masalah di kabel LAN nya

   2. Kita juga bisa menggunakan command ping 8.8.8.8 untuk melihat apakah device kita telah terhubung ke network atau belum

          ping 8.8.8.8
      

      <img src="https://github.com/Chioaji/Pembuatan-kabel-LAN-dan-konfigurasi_Sachio-Aji/assets/126127582/2039e4ad-6830-4b92-9a88-a15c1c64b7d7" width=50% height=50%>

B. Konfigurasi 2 device

   1. Untuk melakukan konfigurasi kita lakukan dengan 2 Laptop yang saling terhubung oleh kabel LAN
   
   2. Lalu pada ke 2 Laptop kita buka bagian Command prompt dan cek ip masing masing

      <img src="https://github.com/Chioaji/Pembuatan-kabel-LAN-dan-konfigurasi_Sachio-Aji/assets/126127582/6cd37513-8d38-4c60-8d56-4272dbbb4845" width=50% height=50%>


      <img src="https://github.com/Chioaji/Pembuatan-kabel-LAN-dan-konfigurasi_Sachio-Aji/assets/126127582/b5104da6-dcad-4c28-9f32-27a61c289bb6" width=50% height=50%>


   3. Jika sudah mendapat Ip masing masing kita bisa mencoba untuk masuk ke user dari laptop lain dengan command ssh usr@IpAdd usr diisi dengan username device lain dan IpAdd diisi 
      dengan ip address  dari device yg ingin kita konfigurasi


          ssh usrname@IpAdd

        <img src="https://github.com/Chioaji/Pembuatan-kabel-LAN-dan-konfigurasi_Sachio-Aji/assets/126127582/4d2836a2-d104-4596-8a99-93f17d306410" width=50% height=50%>

      
       <img src="https://github.com/Chioaji/Pembuatan-kabel-LAN-dan-konfigurasi_Sachio-Aji/assets/126127582/a8333a13-a8db-4ae5-929e-abb886034a52" width=50% height=50%>


   4. Jika kita telah selesai dan ingin keluar dari user bisa dengan command exit

            exit


      <img src="https://github.com/Chioaji/Pembuatan-kabel-LAN-dan-konfigurasi_Sachio-Aji/assets/126127582/38420717-55e3-488f-bcde-1b01804150d7" width=50% height=50%>



       <img src="https://github.com/Chioaji/Pembuatan-kabel-LAN-dan-konfigurasi_Sachio-Aji/assets/126127582/ac9b15e4-c4d9-4ddb-8a15-75129ad14462" width=50% height=50%>


