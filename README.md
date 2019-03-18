# GinoBot (/w Telegram chatbot)
GinoBot : Chatbot Project for subjects of Departement of Informatics, Universitas Nasional

Untuk menjalankan chatbot ini :

  1. Jalankan terlebih dahulu ngrok nya dengan command di terminal :
  
      ./ngrok http 5002
  
      (jika belum ada, donwload : https://ngrok.com/download)
      
  2. Ubah link webhook url yang ada di file credentials.yml di folder credential : 

    telegram:
      access_token: "704590258:AAHE7Hept9vH_zK9E33rtQ7GPeUT6LfvI_s"
      verify: "unasginobot"
      webhook_url: "{taruh link webhooknya disini}/webhooks/telegram/webhook"
      
  3. Jalankan chatbot dengan menggunakan terminal :
  
      python -m rasa_core.run -d models/model_dialogue -u models/model_nlu --port 5002 --credentials credential/credentials.yml
      
      
      
  **Jika ingin menggunakan bot sendiri, ubah access_token dan verify pada file credential.yml 
    sesuai identitas bot anda yang sudah dibuat di botfather   
         
