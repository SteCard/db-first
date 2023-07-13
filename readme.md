Esercizio: Db First

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario. Usate diagram.net per fare la tabella ed esportate quanto fatto in formato png o jpeg. Create la repo e mettete l'immagine all'interno quindi pushate.

/////

Workshop:

ID --> INT
Nome --> VARCHAR(15)
Cognome --> VARCHAR()
Sesso --> ENUM (M, F) // questo campo accetterà solo questi due valori
Data di nascita --> DATE || YEAR (ha un range e pesa meno di INT)
Residenza/Domicilio --> VARCHAR()
Informazioni aggiuntive --> TEXT
CAP --> VARCHAR()
Recapito telefonico --> VARCHAR()
Email --> VARCHAR()
Metodo di pagamento --> VARCHAR() || ENUM(bonifico, paypal, postepay...)

**Se non devo fare operazioni aritmetiche sui numeri utilizzo il VARCHAR()**

**UNSIGNED - Elimina il valore negativo dal campo numerico, raddoppiando il valore positivo**