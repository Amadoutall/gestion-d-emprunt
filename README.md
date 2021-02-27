# gestion-d-emprunt

## Base de données:
* Author


aid      | name 
------------ | -------------
07890        | Jean Paul Sartre
05678        | Pierre de Ronsard

* book 


bid | title | category 
------------ | ------------- | ------------- 
0001 | L'existentialisme est un humanisme | Philosophie
0002 | Huis clos. Suivi de Les Mouches | Philosophie
0003 | Mignonne allons voir si la rose | Poème
0004 | Les Amours | Poème

* Student 

sid | sname | dept 
------------ | ------------- | ------------- 
S15 | toto | Math
S16 | popo | Eco
S17 | fofo | Mécanique

* write


aid      | bid 
------------ | -------------
07890        | 0001
07890        | 0002
05678        | 0003
05678        | 0003

* borrow 

sid | bid | checkout-time | return-time 
------------ | ------------- | ------------- | -------------
S15 | 0003 | 02-01-2020 | 01-02-2020
S15 | 0002 | 13-06-2020 | null
S15 | 0001 | 13-06-2020 | 13-10-2020
S16 | 0002 | 24-01-2020 | 24-01-2020
S17 | 0001 | 12-04-2020 | 01-07-2020

------------------------------
<p align='center'>
  <a href=''> hhgvgs </a> 
 
</p>
