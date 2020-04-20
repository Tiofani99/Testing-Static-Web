# Software Quality And Assurance

Software Quality Assurance adalah proses sistematis untuk memeriksa apakah sebuah
software telah dikembangkan sesuai dengan kebutuhan yang telah ditentukan sebelumnya. 
Proses ini, bisa dilaksanakan oleh seorang QA Tester atau oleh seorang QA Engineer

Repository ini berisi tentang latihan-latihan matakuliah Software Quality And Assurance


*  Buku referensi : 
https://www.obeythetestinggoat.com/book/praise.harry.html


*  **Untuk menjalankan gunakan perintah** <br>
`python manage.py runserver`

<br>
Untuk File penjelasan bisa diakses pada link berikut : <br>
https://drive.google.com/open?id=1b1xNp3qm0CkXs0El0ccBMF7iAFpY813J


# Tentang Excercise 1


Merupakan latihan dari bab 1-3
*  Unit Testing matematika sederhana

>     def test_bad_maths(self):
>         self.assertEqual(1 + 1, 3)


*  Unit testing untung mengecek html dan title
  
  ```
  def test_home_page_returns_correct_html(self):
        request = HttpRequest()  
        response = home_page(request)  
        html = response.content.decode('utf8')  
        self.assertTrue(html.startswith('<html>'))  
        self.assertIn('<title>To-Do lists</title>', html)  
        self.assertTrue(html.endswith('</html>')) 
```
