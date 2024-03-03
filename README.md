Main.java içerisine yazılan sporcu bilgileri ve ring bilgileri ile birlikte boks oyunu çalışacaktır.

Gereken bilgiler; isim, vuruş gücü, sağlık, ağırlık, kaçınma becerisi şekildedir.
Fighter marc = new Fighter("Marc" , 15 , 100, 90, 40);

Ring oluşturulup dövüşçü isimleri ve ağırlık limitleri girilmelidir.
Ring r = new Ring(marc,alex , 90 , 100);

//Orjinal koddan farklı olarak hangi sporcunun önce başlayacağı durumu oluşturulmuştur. Run metodu içine "double baslangic = Math.random() * 100;" şeklinde kod yazılmış ve gelen değere göre oluşturulan dövüş sekansından hangisinin devam edeceğine karar verilecektir.

