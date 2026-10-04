# Web Scraping & Text Preprocessing

Repository ini berisi tugas Web Scraping dan Text Preprocessing menggunakan Python.

## 1. Web Scraping

Pada tugas Web Scraping digunakan dua sumber data, yaitu website Kopi Kenangan dan Wikipedia.

### Kopi Kenangan

Data diambil dari beberapa halaman website Kopi Kenangan menggunakan Requests, BeautifulSoup, dan Pandas.

Halaman yang digunakan:
- About
- News
- Career
- Outlets
- Kenangan Academy

### Wikipedia

Data juga diambil dari halaman Wikipedia mengenai Data Science menggunakan Wikipedia API dan library Requests.

## 2. Text Preprocessing

Pada tugas Text Preprocessing digunakan data review pengguna aplikasi MyTelkomsel dari Google Play Store.

Data review dikumpulkan menggunakan library Google Play Scraper.

Tahapan preprocessing yang dilakukan meliputi:

1. Remove HTML Tags
2. Remove Hashtag
3. Lower Casing
4. Remove URL, HTTP, and E-mail
5. Remove Punctuations
6. Removal of Emojis
7. Remove Stopwords
8. Remove Frequent Words
9. Remove Rare Words
10. Stemmer

Hasil preprocessing berupa teks yang telah dibersihkan dan dapat digunakan untuk tahap analisis teks selanjutnya.

## Tools & Libraries

- Python
- Requests
- BeautifulSoup
- Pandas
- Google Play Scraper
- NLTK
- Sastrawi
- Regex
- WordCloud
- Matplotlib
