## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.
2. Git ile GitHub arasında ne fark var?
Git , yazdığımız projeleri ve uygulamaları, bilgisayarımızda ya da harici disklerde değil de internet üzerinde tutmamızı ve yönetmemizi sağlayan bir versiyon kontrol sistemidir. GitHub, sürüm kontrol sistemi olarak Git kullanan yazılım projeleri için bir depolama servisidir.
3. Neden bir branch oluşturuyoruz?
Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlamak ve kendi repomuz özelinde çatallanma sağlamak için oluşturuyoruz. 
4. Pull Request'in amacı nedir?
Fork ettiğimiz dosyalarda yaptığımız değişiklikleri ana repoya göndermek.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout -b ayse-sahin
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git-fetch - Başka bir depodan nesneleri ve referansları indirme
git merge - İki veya daha fazla geliştirme geçmişini birlikte birleştirin
git-pull - Başka bir havuzdan veya yerel bir şubeden alın ve bunlarla entegre edin
7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
8. Merge conflict'i nasıl çözeriz?
Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.
