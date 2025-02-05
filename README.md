# NotulenEZ
"Program to easily create meeting transcripts and summaries"

Program ini menggunakan beberapa AI yaitu
> Pyannote
  Pyannote digunakan untuk Speaker Diarization – mendeteksi dan memisahkan siapa yang berbicara dalam rekaman audio.
 
> Whisper (Open AI)
  Whisper adalah model Speech-to-Text (STT) dari OpenAI yang digunakan untuk mentranskripsikan audio menjadi teks.

> BART
  Facebook BART digunakan untuk merangkum teks hasil transkripsi agar lebih ringkas dan mudah



- Untuk dapat menjalankan program ini harus menginstall beberapa library
  1. Install library python ini :
     - pip install torch torchvision torchaudio
     - pip install whisper openai
     - pip install transformers
     - pip install pyannote.audio
     - pip install tqdm
     - pip install python-docx
     - pip install tkinter
     - pip install soundfile
     - pip install ffmpeg-python
     
  2. Buat Token Hugging Face
     Buka Hugging Face → 🔗 https://huggingface.co/settings/tokens
     Klik "New Token", beri nama, dan pilih "Read"
     Salin token Anda dan masukkan ke dalam kode:  HF_TOKEN = "hf_xxxxxxxxxxxxxxxxxxxxxxxxxxx"
     
  3. Check CUDA pada GPU
   Jika memiliki GPU NVIDIA, Anda bisa menjalankan:
          ""import torch
          print(torch.cuda.is_available())  # Jika True, berarti bisa menggunakan GPU""
    Untuk mengaktifkan GPU, pastikan sudah menginstal CUDA Toolkit:
    🔗 https://developer.nvidia.com/cuda-downloads




