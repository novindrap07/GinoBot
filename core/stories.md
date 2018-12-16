## main story si 1
* greeting
    - utter_greeting
* tanya_jurusan  
    - action_jurusan
    - slot{"jurusan" : "Sistem Informasi"}
    - utter_pilih_si
* tanya_matkul
    - slot{"matkul" : "Matematika Diskrit"}
* hasil
    - slot{"kode_matkul" : "1708030203", "matkul" : "Matematika Diskrit", "sks" : "2", "semester" : "ganjil", "studi_matkul" : "Studi mengenai dasar – dasar matematika teknologi.", "topik_matkul" : "Himpunan, relasi, fungsi dan proposisi, poset, lattice, dan aljabar boolean.", "software_matkul" : "-"}
    - utter_again       
    - action_restart      
        

## main story si 2
* greeting
    - utter_greeting
* tanya_jurusan  
    - action_jurusan
    - slot{"jurusan" : "Sistem Informasi"}
    - utter_pilih_si
* tanya_matkul
    - slot{"matkul" : "Praktikum Dasar - Dasar Pemrograman I"}
* hasil
    - slot{"kode_matkul" : "1708020204", "matkul" : "Praktikum Dasar - Dasar Pemrograman I", "sks" : "1", "semester" : "ganjil", "studi_matkul" : "Studi tentang dasar pada pemrograman dan logika pemrograman.", "topik_matkul" : "Dasar Logika Pemrograman, Bahasa Pemrograman C++", "software_matkul" : "Dev C++, Netbeans, Turbo C++ 4.5, Microsoft Visual Studio"}
    - utter_again       
    - action_restart      
    
## main story si 3
* greeting
    - utter_greeting
* tanya_jurusan  
    - action_jurusan
    - slot{"jurusan" : "Sistem Informasi"}
    - utter_pilih_si
* tanya_matkul
    - slot{"matkul" : "Praktikum Perancangan Web"}
* hasil
    - slot{"kode_matkul" : "1708020315", "matkul" : "Praktikum Perancangan Web", "sks" : "1", "semester" : "Genap", "studi_matkul" : "Studi mengenai struktur dasar dan pengembangan pada web.", "topik_matkul" : "Definis web, dasar HTML dan CSS. ", "software_matkul" : "Sublime Text 3, Visual Studio Code, Google Web Design"}
    - utter_again       
    - action_restart
    
## main story ti 1   
* greeting
    - utter_greeting
* tanya_jurusan  
    - action_jurusan
    - slot{"jurusan" : "Informatika"}
    - utter_pilih_ti
* tanya_matkul
    - slot{"matkul" : "Algoritma dan Pemrograman I"}
* hasil
    - slot{"kode_matkul" : "1708030201", "matkul" : "Algoritma dan Pemrograman I", "sks" : "2", "semester" : "Ganjil", "studi_matkul" : "Studi tentang dasar pada pemrograman dan logika pemrograman.", "topik_matkul" : "Dasar Logika Pemrograman, Bahasa Pemrograman C++", "software_matkul" : "-"}
    - utter_again       
    - action_restart
    
## main story ti 2   
* greeting
    - utter_greeting
* tanya_jurusan  
    - action_jurusan
    - slot{"jurusan" : "Informatika"}
    - utter_pilih_ti
* tanya_matkul
    - slot{"matkul" : "Praktikum Pemrograman Visual"}
* hasil
    - slot{"kode_matkul" : "1708020347", "matkul" : "Praktikum Pemrograman Visual", "sks" : "1", "semester" : "Genap", "studi_matkul" : "Studi tentang pemahaman lanjut pada pemrograman dan logika pemrograman secara visual.", "topik_matkul" : "Pengenalan pemrograman visual .net 2010, logika pemrograman berbasis visual.", "software_matkul" : "Microsoft Visual Studio"}
    - utter_again       
    - action_restart
     

## main story ti 3   
* greeting
    - utter_greeting
* tanya_jurusan  
    - action_jurusan
    - slot{"jurusan" : "Informatika"}
    - utter_pilih_ti
* tanya_matkul
    - slot{"matkul" : "Praktikum Pemrograman Visual"}
* hasil
    - slot{"kode_matkul" : "1708020347", "matkul" : "Praktikum Pemrograman Visual", "sks" : "1", "semester" : "Genap", "studi_matkul" : "Studi tentang pemahaman lanjut pada pemrograman dan logika pemrograman secara visual.", "topik_matkul" : "Pengenalan pemrograman visual .net 2010, logika pemrograman berbasis visual.", "software_matkul" : "Microsoft Visual Studio"}
    - utter_again       
    - action_restart
    
## failure story
* fallback
    - action_fallback
    - utter_fallback