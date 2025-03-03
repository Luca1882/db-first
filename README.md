# db-first
Tabella Database

Colonna               |      Tipi di Dato      |              Attributi              |
______________________|________________________|_____________________________________|
ID                    |      INT               |      Primary Key/Auto-Increment     |
Marca                 |      Varchar(30)       |              Not Null               |
Modello               |      Varchar(40)       |              Not Null               |
anno_immatricolazione |      Year              |              Not Null               |
Telaio                |      Varchar(17)       |          Not Null/Unique            |
Alimentazione         |      Varchar(20)       |              Not Null               |
Colore                |      Varchar(20)       |              Not Null               |
Disponibilità         |      Boolean           |              Default (1,0)          |
