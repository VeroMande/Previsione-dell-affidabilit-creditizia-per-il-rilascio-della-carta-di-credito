# Previsione-dell-affidabilit-creditizia-per-il-rilascio-della-carta-di-credito
Previsione dell'affidabilità creditizia per il rilascio della carta di credito

Sei stato assunto dalla Pro National Bank come data scientist, il tuo primo incarico consiste nel realizzare un modello in grado di stimare l'affidabilità creditizia di un clienti, al fine di di aiutare il team dedicato a comprendere se accettare o meno la richiesta per il rilascio della carta di credito.

A tal fine ti vengono consegnati i dati anonimizzati di clienti che hanno già ottenuto la carta di credito e ne pagano regolarmente le rate. 

I dati sono in un file CSV presente a questo indirizzo: https://proai-datasets.s3.eu-west-3.amazonaws.com/credit_scoring.csv

Il file credit_scoring.csv contiene le informazioni dei correntisti che hanno richiesto l’apertura di una linea di credito.

|Feature name|Explanation| 
|:---|:---|
|ID| numero identificativo del cliente |
|CODE_GENDER|sesso del cliente|
|FLAG_OWN_CAR|indicatore del possesso di un'automobile |
|FLAG_OWN_REALTY|indicatore del possesso di una casa |
|CNT_CHILDREN| Numero di figli |
|AMT_INCOME_TOTAL|Reddito annuale|
|NAME_INCOME_TYPE| tipo di reddito|
|NAME_EDUCATION_TYPE| livello di educazione |
|NAME_FAMILY_STATUS|stato civile|
|NAME_HOUSING_TYPE|stile di vita|
|DAYS_BIRTH|Numero di giorni trascorsi dalla nascita|
|DAYS_EMPLOYED|Numero di giorni trascorsi dalla data di assunzione, se positivo indica il numero di giorni da quando è disoccupato|
|FLAG_MOBIL| indicatore della presenza di un numero di cellulare|
|FLAG_WORK_PHONE| indicatore della presenza di un numero di telefono di lavoro |
|FLAG_PHONE| indicatore della presenza di un numero di telefono |
|FLAG_EMAIL|indicatore della presenza di un indirizzo email |
|OCCUPATION_TYPE|tipo di occupazione|
|CNT_FAM_MEMBERS|numero di familiari|
|TARGET|una variabile che vale 1 se il cliente ha una elevata affidabilità creditizia data dal pagamento costante delle rate e 0 altrimenti |

Devi realizzare un modello che preveda il target dato.

## PUNTO BONUS
Se ad un cliente viene negata la carta di credito, il team deve essere in grado di fornirgli una motivazione, questo vuol dire che il tuo modello deve fornire delle indicazioni facilmente interpretabili.
