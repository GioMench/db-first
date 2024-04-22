##
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
##

DB_NAME : concessonario

tabella : auto usate

- id | INDEX |  INT OR BIGINT
- marchio | INDEX | VARCAHR(50)
- modello | INDEX | VARCHAR(50)
- chilometraggio | INT O DECIMAL?
- anno | YEAR 
- tipo di cambio | VARCHAR(50)
- carburante | VARCHAR(50)
- potenza | SMALLINT
- cilindrata |  SMALLINT
- classe emissioni | CHAR(6)
- carrozzeria | VARCHAR(200)
- prezzo | DECIMAL
- venditore | VARCHAR(50)
- note | TEXT 