## story_si_2
* greeting
    - utter_greeting
    - utter_jurusan
* jurusan{"jurusan": "sistem informasi"}
    - slot{"jurusan": "sistem informasi"}
    - slot{"jurusan": "sistem informasi"}
    - utter_pilih_si
    - utter_matkul
* matkul_si
    - action_infomatkul
    - utter_so   <!-- predicted: utter_pkn -->
    - utter_bye


## story_ti_2
* greeting
    - utter_greeting
    - utter_jurusan
* jurusan{"jurusan": "informatika"}
    - slot{"jurusan": "informatika"}
    - slot{"jurusan": "informatika"}
    - utter_pilih_ti
    - utter_matkul
* matkul_ti
    - action_infomatkul
    - utter_agama   <!-- predicted: utter_ddp -->
    - utter_bye


