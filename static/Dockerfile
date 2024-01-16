# Gunakan image Python sesuai dengan versi yang terinstall sebagai dasar
FROM python:3.11.6

# Set direktori kerja dalam container
WORKDIR /app

COPY . /app

# Install dependensi proyek dari berkas requirements.txt
RUN pip install -r requirements.txt

# Expose port yang akan digunakan oleh aplikasi Flask
EXPOSE 9000

# Perintah yang akan dijalankan saat container berjalan
CMD ["python3", "app.py"]

