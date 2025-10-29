Modellizzare la struttura di un database per memorizzare tutti i dati riguardanti una università:

## Table: dipartimenti

- id
- nome_del_dipartimento
- indirizzo
- numero
- email

## Table: corsi di laurea

- id
- dipartimento_id
- nome
- indirizzo
- email
- livello

## Table: corsi

- id
- corso_di_laurea_id
- nome
- descrizione
- anno

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
- corso_id
- studente_id
- voto
- crediti
- data_esame

### Table: esame_studente

- esame_id
- studente_id

## Table: studenti

- id
- corso_di_laurea_id
- nome
- cognome
- libretto
- email
- telefono
- indirizzo