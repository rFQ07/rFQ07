BEGIN
   Ambil spidol
   IF tinta_habis THEN
       Ganti spidol
   ELSE
       Tekan ujung spidol di kertas
       IF tinta_keluar THEN
           Gunakan spidol
       ELSE
           Rendam ujung spidol dengan air/alkohol
           Coba menulis lagi
           IF tinta_keluar THEN
               Gunakan spidol
           ELSE
               Gunakan spidol lain
           ENDIF
       ENDIF
   ENDIF
END
