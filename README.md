# db-auto-usate

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

### Auto
- id_auto (PK) *NOT NULL VARCHAR(50)*
- marca *NOT NULL VARCHAR(50)*
- modello *NOT NULL VARCHAR(50)*
- anno_immatricolazione *NOT NULL YEAR*
- chilometraggio *NOT NULL INT*
- prezzo *NOT NULL DECIMAL(10,2)*
- tipo_carburante *VARCHAR(20)*
- colore *VARCHAR(20)*
- data_annuncio *DATE*
- descrizione *TEXT*