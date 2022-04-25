[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-green)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

# Mengamankan Aplikasi Web Berbahasa GO

## Perkenalan

Catatan ini berisi bagaimana cara membangun / membuat aplikasi yang aman berdasarkan Bahasa Pemrograman GO. Catatan ini juga bertujuan untuk membantu *developer* menghindari kesalahan umum terkait keamanan aplikasi yang dibuat.

## Input Validation

Di dalam kemanan aplikasi yang dibuat, *input* yang dibuat oleh pengguna beserta data yang di-*input* merupakan risiko kemanan apabila dibiarkan tanpa pengecekan / validasi. Validasi terhadap *input user* harus dilakukan di semua aplikasi yang mensyaratkan pengguna memasukkan data / mengisikan data. Berikut merupakan detail dari tahapan *Input Validation* beserta contohnya,

### User Interactivity

Setiap bagian dari aplikasi yang memungkinkan pengguna memasukkan data merupakan risiko keamanan yang potensial. Masalah dapat terjadi bukan hanya karena sengaja *attack* melainkan juga dapat salah *input* oleh pengguna. Pada Go-Lang ada beberapa cara untuk meminimalisir kesalahan tersebut.

- `strconv` berfungsi mengonversi *string* ke tipe data lain
  
  **Atoi**
  
  ```go
  func Atoi(s string) (int, error)
  ```
  
  > `Atoi` setara dengan `ParseInt(s, 10, 0)`, dikonversi ke tipe `int`.

- dsaf

- 

# References
- GitHub Go SCP. 2022. GitHub - OWASP/Go-SCP: Go programming language secure coding practices guide. [online] Available at: <https://github.com/OWASP/Go-SCP> [Accessed 25 April 2022].
- Owasp.org. 2022. OWASP Top 10 Web App. [online] Available at: <https://owasp.org/Top10/> [Accessed 25 April 2022].
