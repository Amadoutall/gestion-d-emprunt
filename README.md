# Système de gestion d’emprunt dans une librairie

### @author: Amadou tall, Cheikh Diop, Régis Aymar Bambou

## description des tables:  
**book:**  
représente une table d'auteurs. Chaque ligne contient le nom et l'identifiant d'un auteur book représente une table de livres. Chaque ligne est un livre décrit par son identifiant, son titre et sa catégorie (roman, science-fiction, musique, etc.).  
  
**student:**  
représente une table d'étudiants. Chaque ligne est un étudiant décrit par son identifiant, son nom et son département (informatique, mécanique...). 
  
**write:**  
représente l'association entre les auteurs et les livres. Une ligne de cette table signifie que l'auteur a écrit le livre bid. 
  
**borrow:**  
représente les informations de prêt de livre. Une ligne de cette table signifie que l'étudiant a emprunté le livre bid, à la date checkout-time et l'a retourné à la date return-time. 

## Bases de données:

**Author**


aid      | name 
------------ | -------------
07890        | Jean Paul Sartre
05678        | Pierre de Ronsard

**book** 


bid | title | category 
------------ | ------------- | ------------- 
0001 | L'existentialisme est un humanisme | Philosophie
0002 | Huis clos. Suivi de Les Mouches | Philosophie
0003 | Mignonne allons voir si la rose | Poème
0004 | Les Amours | Poème

**Student** 

sid | sname | dept 
------------ | ------------- | ------------- 
S15 | toto | Math
S16 | popo | Eco
S17 | fofo | Mécanique

**write**


aid      | bid 
------------ | -------------
07890        | 0001
07890        | 0002
05678        | 0003
05678        | 0003

**borrow**

sid | bid | checkout-time | return-time 
------------ | ------------- | ------------- | -------------
S15 | 0003 | 02-01-2020 | 01-02-2020
S15 | 0002 | 13-06-2020 | null
S15 | 0001 | 13-06-2020 | 13-10-2020
S16 | 0002 | 24-01-2020 | 24-01-2020
S17 | 0001 | 12-04-2020 | 01-07-2020

------------------------------
<p align='center'>
  <a href='https://www.linkedin.com/in/regis-aymar-bambou-0733b11a4/'> <img src="images/174857.png">  images </img>  </a> 
 
</p>
