# Kamus Kata Ambon
Ambon adalah sebuah pulau yang terletak di tengah-tengah Kepulauan Maluku, Indonesia. Pulau ini dikenal karena pesonanya yang alami dan beragam, dengan pemandangan indah yang mencakup perbukitan hijau, pantai berpasir putih, dan air laut yang jernih. Namun, sejarah Ambon juga memiliki lapisan yang mendalam. 

Pulau Ambon memiliki sejarah panjang yang mencakup periode penjajahan oleh berbagai kekuatan kolonial. Pada abad ke-16, bangsa Portugis pertama kali tiba di pulau ini dan mendirikan benteng-benteng sebagai pos perdagangan rempah-rempah yang sangat berharga. Namun, mereka kemudian digantikan oleh Belanda yang menguasai Ambon pada abad ke-17 setelah pertempuran sengit dan perjanjian dengan Portugis. Selama berabad-abad, pulau ini menjadi pusat perdagangan rempah-rempah penting, terutama cengkih dan pala, yang sangat diminati oleh pedagang Eropa.

Selama masa penjajahan Belanda, Ambon mengalami berbagai periode ketegangan dan pemberontakan oleh penduduk asli yang menentang penindasan dan eksploitasi kolonial. Selama masa ini, sejarah Ambon mencatat perlawanan berani oleh masyarakat pribumi, termasuk Perang Pattimura pada awal abad ke-19 yang dipimpin oleh Kapitan Pattimura. Meskipun upaya untuk mendapatkan kemerdekaan dari penjajahan Belanda belum berhasil pada saat itu, semangat perlawanan ini menjadi bagian penting dari warisan budaya Ambon.

Sejarah Ambon yang panjang dan beragam ini mencerminkan perjalanan pulau ini dari masa kolonial hingga masa kemerdekaan Indonesia, dan juga menyiratkan makna yang lebih dalam mengenai identitas budaya dan keberanian penduduknya dalam menghadapi berbagai tantangan sepanjang sejarah.

Kamus Bahasa Ambon ini menggabungkan kata-kata dari Kamus Bahasa Ambon yang diterbitkan pada tahun 1998 oleh D. Takaria dan C. Pieter dengan istilah-istilah yang diambil dari Alkitab Melayu (Ambon).

Jika anda ingin mengakses menggunakan google colab 
```python
# URL repositori GitHub
github_url = "https://raw.githubusercontent.com/Airukua/Kamus_Ambon/master/kamus_alk_ambon.txt"

# Lokasi tempat Anda ingin menyimpan file yang diunduh
file_path = "kamus_alk_ambon.txt"

# Mengunduh file dari URL
!wget.download(github_url, out=file_path)

print(f"File '{file_path}' telah diunduh.")
```
kemudian anda dapat membukanya menggunakan library pandas

```python
df = pd.read_csv(file_path, header=None, encoding='iso-8859-1')
```
