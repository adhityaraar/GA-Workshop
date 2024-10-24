# Building  Apps with Streamlit

# HuggingFace API Setup
1. Sign In or Sign Up on [Click](https://huggingface.co/).
2. Go to Profile (avatar) and click on "Settings".
3. Go to "Access Token" and click on "New token".
4. Give a user-friendly name to the token and permission=write. Then click on generate token.
5. Copy the token and add it in your .env file. `HUGGINGFACEHUB_API_TOKEN=<your_new_huggingface_access_token>`
6. Model Request (Example: Go to [meta-llama card](https://huggingface.co/meta-llama) or [meta-llama-3.1-8b card](https://huggingface.co/meta-llama/Llama-3.1-8B)
   
# Pineccone API Setup
1. Sign In or Sign Up on [Click](https://www.pinecone.io/).
2. Go to API Keys

# Startup
1. Open your terminal or console window
2. cd into this lab's base directory
3. Copy your .env file into this lab's base folder
4. Add HuggingFaceToken to .env file. See the HuggingFace API Setup section below.
5. Run the app by running the command `streamlit run app.py`.
6. You can ask example questions in Bahasa

### Contoh Pertanyaan:
- Pertanyaan easy
    - Pada pukul berapa karyawan mulai bekerja?
    - Berapa usia pensiun karyawan?
    - Berapa lama masa percobaan karyawan baru?
    
    Apa yang dimaksud dengan cuti karyawan?
    
- Pertanyaan medium
    - Kapan gaji akan dibayarkan jika tanggal 25 jatuh pada hari Sabtu?
    - Apa yang harus dilakukan karyawan jika ingin menggunakan hak cuti tahunannya?
    - pakaian apa yang digunakan pada hari Selasa?
    
- Pertanyaan hard
    - Apa saja tunjangan yang dapat diterima karyawan yang telah bekerja minimal 12 bulan di perusahaan, dan bagaimana aturan terkait Tunjangan Hari Raya (THR) untuk karyawan yang berhenti bekerja paling lama 30 hari sebelum hari raya Idul Fitri?
    - Bagaimana perusahaan mengevaluasi performa karyawan baru selama masa percobaan, dan siapa yang terlibat dalam proses pengawasan dan penilaian?
    - Bicarakan mengenai jaminan sosial karyawan yang diberikan oleh perusahaan, termasuk hak karyawan yang meninggal dan hak keluarga karyawan yang meninggal dalam hal jaminan sosial.
