Önizleme için(bakmak için) eski bir commite dönmek -->

normalde git checkout branchler arasında geçiş için kullanılır
fakat commit id'si verirseniz önceki commitleri de incelemenize yarar

git checkout commitid
<hr>

bunu kullanınca idsini verdiğiniz committeki kodları görürsünüz -->
tekrardan en son commit geri dönmek için git checkout ile dal ismini kullanırız.

git checkout branch

<hr>

## BRANCH

# Yeni branch oluşturma

> ÖRN: git branch frknecn3/html

Bu komut branchi oluşturur fakat direkt olarka içine giriş yapmaz.

# Branche geçiş yapmak

> git checkout branch-ismi(ya da commitid)

> ÖRN: git checkout frknecn3/html

# Hem branch aç hem de anında geçiş yap

> git checkout -b tahaserdar/css

# Başka bir branchin değişikliklerini almak için

> git merge branch-ismi

> ÖRN: git merge main YA DA git merge frknecn3/html


# Branch silmek için (delete)

> git branch -d tahaserdar/css





<!-- ------------------------------ MERGE CONFLICT -->