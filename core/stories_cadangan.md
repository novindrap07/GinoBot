## story_si
* greeting
  - action_greeting
  - utter_tanya_jurusan
* tanya_jurusan{"jurusan": "Sistem Informasi"}
  - action_jurusan
  - utter_pilih_si
  - utter_tanya_matkul
* tanya_matkul{"matkul": "Pemrograman Visual"}
  - action_matkul
* hasil{"kode_matkul": "1708020346", 
        "matkul": "Pemrograman Visual",
        "sks": "2",
        "semester": "Ganjil",
        "studi_matkul": "Studi tentang pemahaman lanjut pada pemrograman dan logika pemrograman secara visual.",
        "topik_matkul": "Pengenalan pemrograman visual .net 2010, logika pemrograman berbasis visual.",
        "software_matkul": "-",
        "sesi_matkul": "",
        "mahasiswa_matkul": "Rikza, Salma, Tiara, Umairah, Vina, Wildan, Xavier, Yoga, Zaskia.",
        "referensi_matkul": "https://goo.gl/cVgHWX"}
  - action_hasil
  - utter_hasil 
  - utter_restart  
  
## story_ti
* greeting
  - action_greeting
  - utter_tanya_jurusan
* tanya_jurusan{"jurusan": "informatika"}
  - action_jurusan
  - utter_pilih_ti
  - utter_tanya_matkul
* tanya_matkul{"matkul": "Cloud Computing"}
  - action_matkul
* hasil{"kode_matkul": "1708030602", 
        "matkul": "Cloud Computing",
        "sks": "2",
        "semester": "Genap",
        "studi_matkul": "Studi mengenai pemanfaatan teknologi komputasi dan pengembangan internet berbasis awan.",
        "topik_matkul": "Services cloud computing, Implementasi cloud computing di era sekarang.",
        "software_matkul": "-",
        "sesi_matkul": "20.30 - 21.30",
        "mahasiswa_matkul": "Rikza, Salma, Tiara, Umairah, Vina, Wildan, Xavier, Yoga, Zaskia.",
        "referensi_matkul": "https://goo.gl/JMTs1H"}  
  - action_hasil
  - utter_hasil 
  - utter_restart
  
## failure story
* fallback
  - action_default_fallback
  - utter_default_fallback    