# Bash_shell.
# Simple read&write code using bash shell.
# My simple roadmap, how to learn Bash Shell step-by-step.


1.Intro
  Bash shell adalah bahasa shell Unix atau script pada terminal untuk menjalankan  perintah di linux 
  dan MacOS.

  - Hello World
  
  
  - Komentar 
    (comment) bagian dari program yang tidak perlu dieksekusi.Bagian hanya digunakan agar program mudah di pahami.Komentar sendiri di bagi mnejadi dua 
    yaitu;
          1. Single Line
             Menambahkan komentar pada satu line. Biasa menggunakan tanda pagar '#'.
            
          2. Multi Line
             Menambahkan komentar pada satu baris. Bisa menggunakan tanda pagar '#' atau HereDoc.HereDoc bisa menampung komentar pada satu baris,namun ini masih 
             kurang efisien jadi disarankan menggunakan tanda pagar '#'.
  - Variable
    adalah suatu tempat yang digunakan untuk menampung data atau nilai pada memori yang mempunyai nilai yang dapat berubah–ubah dalam proses program.Di Bash
    ada beberapa jenis variable yang di bisa kelompokan berdasarkan fungsi atau kegunaannya. Variable di kelompokan menjadi;
      > Enviroment Variable
        - Digunakan untuk shell system .
        - Biasa menggunakan huruf kapital.
        - Untuk mengetahui apa saja enviroment pada system, ketikan perintah 'env', tanpa tanda 
          petik.
          Contoh; $HOSTNAME, $USER, $HOME dll.
        
       > Parameter Variable
         Digunakan untuk menampung beberapa argumen sekaligus dalam shell. Biasa menggunakan 
         tanda “$”.
         Contoh; $1, $2, $3 dll.
         
       > User Defined Variable
         Biasa digunakan oleh penulis sendiri untuk menjalankan beberapa perintah dalam satu shell.Sama persis dengan Parameter Variable. Biasa menggunakan
         angka atau underscore "-" tinggal eksekusinya menggunkan '$'.
         Contoh; Dimana='Danau'; >> $Dimana. 
          



  
  
  
  