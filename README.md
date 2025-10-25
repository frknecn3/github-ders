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
# Bu özellik, şuan içinde olduğunuz branche kod ekler, merge yaptığınız branchin kodunda ASLA değişiklik olmaz.

> git merge branch-ismi

> ÖRN: git merge main YA DA git merge frknecn3/html


# Branch silmek için (delete)

> git branch -d tahaserdar/css





<!-- ------------------------------ MERGE CONFLICT -->

# MERGE CONFLICT

MERGE CONFLICT SADECE yeni bir branch açtıktan sonra
ana branch'e yeni bir commit geldiğinde olur.

main --> oznur/yeni-ozellik

SONRA

main'e yeni commit geldi (taha bey js'i editledi)

SONRA

öznur hanım değişikliklerini bitirdi ve artık merge yapacak

git checkout main

git merge oznur/yeni-ozellik

ÇAKIŞMA OLUR

Ya Taha beyin değişikliklerini kabul ederiz ya da öznur hanımın
ardından kabul ettiğimiz değişiklikleri tekrardan commitleriz ve öznur hanımın alt branchini sileriz.

