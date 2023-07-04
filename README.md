# menu
****
### SCREENSHOT
![](/screenshot.png)
***

ASIAN KITCHEN MENU ADIMLARI

1.	menu adında bir dizi oluşturulur. Bu dizi, yemeklerin bilgilerini içeren nesneleri içerir.
2.	section ve btnContainer isimli HTML elementleri, document.querySelector yöntemiyle seçilir.
3.	categories adında bir değişken oluşturulur ve menu dizisindeki yemeklerin kategorilerini içerir. Bu kategoriler, reduce yöntemi kullanılarak values adında boş bir diziye eklenir. "All" değeri de başlangıçta values dizisine eklenir.
4.	categoryList adında bir fonksiyon tanımlanır. Bu fonksiyon, kategori düğmelerini oluşturur.
5.	categories dizisi üzerinde map yöntemi kullanılarak her bir kategori için bir düğme HTML içeriği oluşturulur. Daha sonra btnContainer elementinin innerHTML özelliği bu içerikle güncellenir.
6.	Kategori düğmeleri seçilir ve her birine bir click olayı dinleyicisi eklenir.
7.	Tıklanan düğmenin data-id özelliği aracılığıyla kategori bilgisi alınır.
8.	menu dizisi, seçilen kategoriye göre filtrelenir ve menuCategory adında yeni bir dizi oluşturulur.
9.	Eğer seçilen kategori "All" ise, tüm menü öğeleri menuList fonksiyonuna geçilir. Aksi halde, menuList fonksiyonu menuCategory dizisi ile çağrılır.
10.	menuList adında bir fonksiyon tanımlanır. Bu fonksiyon, menü öğelerini HTML içeriği olarak oluşturur.
11.	menuItems parametresiyle alınan dizi üzerinde map yöntemi kullanılarak her bir öğe için HTML içeriği oluşturulur.
12.	Oluşturulan HTML içerikleri birleştirilerek displayMenu adında bir dize oluşturulur.
13.	displayMenu dizesi, section elementinin innerHTML özelliğiyle güncellenir.
14.	Son olarak, menuList ve categoryList fonksiyonları sırasıyla menu dizisiyle ve kategori düğmeleriyle çağrılır, böylece sayfa başlangıçta menüyü ve kategori düğmelerini gösterir.
