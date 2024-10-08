Assesment:
1. Apa kegiatan yang dilakukan dan berapa lama kalian melakukan capturing packet.
   
   Melakukan capturing packet menggunakan Wireshark, yaitu menganalisis lalu lintas jaringan (network traffic) selama ±15 menit, Kegiatan yang dilakukan meliputi
   - Streaming Video
   - Game Online
   - Download dan Upload File
     
2. Buatlah tabel hasil pengukuran dari Throughput, Packet Loss, Delay, dan Jitter.
   ![image](https://github.com/user-attachments/assets/d5b4dc0e-9654-46ec-b05a-8dfc58c27462)


3. Tulislah hasil perhitungan dengan rumus dari Throughput, Packet Loss, Delay, dan Jitter.
   
   a) Throughput:
      Throughput mengukur kecepatan data yang dikirimkan melalui jaringan dalam satuan bit per detik (bps). Untuk menghitung throughput dari data Wireshark:
    	Rumus:
      -	Total Bytes = 87,401,392 Bytes
      -	Time Span = 1,036.580 detik
      -	Konversi Byte ke Bit: 87,401,392 Bytes x 8 = 699,211,136 bits
      -	Hitung Throughput: 699,211,136 bits / 1,036.580 detik ≈ 674,416 bps atau 674 kbps
        
   b) Packet Loss
      Packet Loss adalah persentase paket yang hilang selama transmisi
      -	Packet Loss = (Paket yang hilang / Total paket yang dikirim) x 100.
      -	Packet Loss = (93,352 - 93,352) / 93,352 x 100 = 0%
        
   c) Delay
      Delay mengukur waktu yang diperlukan untuk paket data berpindah dari sumber ke tujuan dalam milidetik.
      Tidak ada data waktu (timestamp) paket, sehingga delay tidak dapat dihitung.
   
   d) Jitter
      Jitter mengukur variabilitas waktu delay antara paket-paket yang berturut-turut.
      Karena tidak ada data delay, jitter juga tidak bisa dihitung.

4. Buatlah tabel indeks yang didapatkan dari pengukuran Quality of Service (QoS).
    | Pengukuran      | Keterangan               | Indeks       | Kategori          |
    |-----------------|--------------------------|--------------|-------------------|
    | Throughput      | 674 kbps                 | 3            |        Baik       |
    | Packet Loss     | 0%                       | 5            |    Sangat Baik    |
    | Delay           | -                        |      -       |         -         |  
    | Jitter          | 2.5 ms                   |      -       |         -         |
    | Rata-Rata Indeks| -                        | 4            |Baik -Sangat Baik  |
   
5. Kesimpulan
   Berdasarkan hasil analisis pengukuran Quality of Service (QoS):
    - Throughput dari jaringan yang diuji menunjukkan performa yang baik dengan nilai 674 kbps.
    - Packet Loss yang tercatat adalah 0%, menunjukkan bahwa tidak ada paket yang hilang selama proses transmisi.
    - Karena tidak ada data timestamp pada file yang diuji, pengukuran Delay dan Jitter tidak dapat dilakukan.
    - Rata-rata indeks QoS yang didapatkan dari pengukuran Throughput dan Packet Loss berada pada kategori Baik-Sangat Baik dengan nilai rata-rata indeks 4.
      
6. Sumber/referensi/daftar pustaka.
   
   Yudi Ariwibowo. (2021). Menghitung Throughput, Packet Loss, Delay dan Jitter Menggunakan Wireshark. Retrieved from https://youtu.be/RgPhJ0r7duk?si=yf23bnVFPGUv9KSC

   Gunawan alfarizi. (2013). Menghitung Throughput, Delay Dan Packet Loss Menggunakan Wireshark dan Rumus. Retrieved from          
   https://gunawanalfarizi.blogspot.com/2013/11/menghitung-throughput-delay-dan-packet.html

   Wireshark Documentation: https://www.wireshark.org/docs/wsug_html_chunked/
   
   Tanenbaum, Andrew S. (2003). Computer Networks. 4th Edition. Pearson.
   
   Kurose, James F., and Keith W. Ross. (2017). Computer Networking: A Top-Down Approach. 7th Edition. Pearson.
   
    
 


