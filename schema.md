Modellizzare la struttura di un database per memorizzare tutti i dati riguardanti una università:

## Table: dipartimenti

- id
- lettere
- filosofia
- matematica
- ingenieria

## Table: corsi di laurea

- id
- dipartimento_id
- civiltà
- letterature_classiche
- informatica
- ingegneria_informatica

## Table: corsi

- id
- corso_di_laurea
- letteratura_latina
- sistemi_operativi 1
- Analisi_matematica 2

## Table: apelli

- id
- 1
- 2
- 3

## Table: appello_corso

- appello_id
- corso_id

## Table: corso_insegnante

- corso_id
- insegnante_id

## Table: insegnanti

- id
- nome
- cognome
- email
- telefono

## Table: esame

- id
- appello_id
- corso_id
- studente_id
- voto
- crediti
- data_esame

## Table: studenti

- id
- corso_di_laurea_id
- nome
- cognome
- libretto
- email
- telefono
- indirizzo