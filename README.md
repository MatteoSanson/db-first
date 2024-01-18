# Esercizio DB First

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
<br><br>

## Modello
![auto-db-first](https://github.com/MatteoSanson/db-first/assets/128544980/598de5b2-1054-49a7-87c1-50fe5777ef7a)

<br>

### Considerazioni sulle colonne

1) **AutoID**: E' l'identificativo univoco per ogni auto inserita (chiave primaria).
2) **marca**: Marchio corrispettivo dell'auto (TOYOTA, AUDI, etc.).
3) **modello**: nome o sigla del modello (A1, DBX, Giulietta, etc.).
4) **allestimento**: nome o sigla dell'allestimento.
5) **alimentazione**: verrà indicata che tipologia di alimentazione adotta l'auto se benzina, ibrida, elettrica, etc.
6) **cilindrata**: numero di cilindrata del mezzo.
7) **potenza_cv**: numero di cavalli.
8) **potenza_kw**: numero di kw.
9) **cambio**: verrà indicata la tipologia di cambio (manuale, automatico, etc.).
10) **anno_produzione**: anno in cui l'auto è stata prodotta.
11) **data_immatricolazione**: mese/anno in cui l'auto è stata immatricolata.
12) **km**: chilometraggio dell'auto.
13) **stato**: condizione dell'auto usata (esposizione, auto aziendale, come nuova, etc.).
14) **segmento**: tipologia di volume dell'auto (A, B, SUV-City, etc.).
15) **n_posti**: numero di posti omologati dell'auto.
16) **n_porte**: numero di porte dell'auto.
15) **EURO**: standard europeo per la misurazione dell'inquinamento generato da un autoveicolo (da 0 a 6 più sigle).
16) **colore**: colore del mezzo.
17) **prezzo**: prezzo di vendita dell'auto.
18) **descrizione**: descrizione del mezzo in vendita.
19) **data_inserimento**: quando viene inserito l'annuncio di vendita.
20) **disponibile**: indica se l'auto è disponibile o no.