## story_si_1
* greeting
  - utter_greeting
  - utter_jurusan
* jurusan{"jurusan": "sistem informasi"}
  - slot{"jurusan": "sistem informasi"}
  - utter_pilih_si
  - utter_matkul
* matkul_si
  - action_infomatkul
  - utter_pkn
  - utter_bye

## story_si_2
* greeting
  - utter_greeting
  - utter_jurusan
* jurusan{"jurusan": "sistem informasi"}
  - slot{"jurusan": "sistem informasi"}
  - utter_pilih_si
  - utter_matkul
* matkul_si
  - action_infomatkul
  - utter_so
  - utter_bye

## story_ti_1
* greeting
  - utter_greeting
  - utter_jurusan
* jurusan{"jurusan": "informatika"}
  - slot{"jurusan": "informatika"}
  - utter_pilih_ti
  - utter_matkul
* matkul_ti  
  - action_infomatkul
  - utter_ddp
  - utter_bye
  
## story_ti_2
* greeting
  - utter_greeting
  - utter_jurusan
* jurusan{"jurusan": "informatika"}
  - slot{"jurusan": "informatika"}
  - utter_pilih_ti
  - utter_matkul
* matkul_ti
  - action_infomatkul
  - utter_agama
  - utter_bye  
  
## fallback_story
* salah_data
  - action_default_fallback  
  - utter_salah