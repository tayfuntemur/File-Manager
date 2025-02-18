# File-Manager
Dosya yönetim sistemi
## Kurulum
1. Repository'yi klonlayın:
  cd FileManager
  https://github.com/tayfuntemur/File-Manager/blob/main/FileManager.rar

3. Sanal ortam oluşturun ve aktifleştirin:
  python -m venv .venv
  .venv\Scripts\activate  # Windows için
  source .venv/bin/activate  # Linux/Mac için
4. Bağımlılıkları yükleyin:
   pip install -r requirements.txt

## Çalıştırma
  streamlit run filemanager.py

## Acıklamalar 
zipfile, logging, re, streamlit, pathlib, cryptography.fernet, datetime kütüpaneleri
kullanilarak;
- fernet ile bir anahtar dosyasi olusturmak,
- bu anahtar ile dosyamızı encrypt yaparak şifrelemek,
- bu anahtar ile dosyamız decrypt yaparak şifreyi çözmek,
- searc yaparak dosyamızda aradağımız kelimeyi bulmak
- bir zip klasörü oluşturararak dosyamızın yedeğini almak,
- ve yedeği tekrak geri yüklemek.


