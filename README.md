# Esercizio

### STEP 1 - RAW Database

Modellizzare la struttura di un database per memorizzare tutti i dati riguardanti una università:
- Sono presenti diversi Dipartimenti (es.: Lettere e Filosofia, Matematica, Ingegneria ecc.);
- Ogni Dipartimento offre più Corsi di Laurea (es.: Civiltà e Letterature Classiche, Informatica, Ingegneria Elettronica ecc..);
- Ogni Corso di Laurea prevede diversi Corsi (es.: Letteratura Latina, Sistemi Operativi 1, Analisi Matematica 2 ecc.);
- Ogni Corso può essere tenuto da diversi Insegnanti;
- Ogni Corso prevede più appelli d'Esame;
- Ogni Studente è iscritto ad un solo Corso di Laurea;
- Ogni Studente può iscriversi a più appelli di Esame;
- Per ogni appello d'Esame a cui lo Studente ha partecipato, è necessario memorizzare il voto ottenuto, anche se non sufficiente;

Pensiamo a quali entità (tabelle) creare per il nostro database e cerchiamo poi di stabilirne le relazioni. Infine, andiamo a definire le colonne e i tipi di dato di ogni tabella.

### STEP 2 - SELECT

- Selezionare tutti gli studenti nati nel 1990 (160);
- Selezionare tutti i corsi che valgono più di 10 crediti (479);
- Selezionare tutti gli studenti che hanno più di 30 anni;
- Selezionare tutti i corsi del primo semestre del primo anno di un qualsiasi corso di laurea (286);
- Selezionare tutti gli appelli d'esame che avvengono nel pomeriggio (dopo le 14) del 20/06/2020 (21);
- Selezionare tutti i corsi di laurea magistrale (38);
- Da quanti dipartimenti è composta l'università? (12);
- Quanti sono gli insegnanti che non hanno un numero di telefono? (50);

### STEP 3 - GROUP BY

- Contare quanti iscritti ci sono stati ogni anno;
- Contare gli insegnanti che hanno l'ufficio nello stesso edificio;
- Calcolare la media dei voti di ogni appello d'esame;
- Contare quanti corsi di laurea ci sono per ogni dipartimento;

### STEP 4 - JOIN

- Selezionare tutti gli studenti iscritti al Corso di Laurea in Economia;
- Selezionare tutti i Corsi di Laurea Magistrale del Dipartimento di Neuroscienze;
- Selezionare tutti i corsi in cui insegna Fulvio Amato (id=44);
- Selezionare tutti gli studenti con i dati relativi al corso di laurea a cui sono iscritti e il relativo dipartimento, in ordine alfabetico per cognome e nome;
- Selezionare tutti i corsi di laurea con i relativi corsi e insegnanti;
- Selezionare tutti i docenti che insegnano nel Dipartimento di Matematica (54);
- BONUS: Selezionare per ogni studente il numero di tentativi sostenuti per ogni esame, stampando anche il voto massimo. Successivamente, filtrare i tentativi con voto minimo 18;