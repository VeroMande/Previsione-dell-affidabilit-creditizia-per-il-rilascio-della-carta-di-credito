# Previsione-dell-affidabilit-creditizia-per-il-rilascio-della-carta-di-credito
Previsione dell'affidabilità creditizia per il rilascio della carta di credito

Sei stato assunto dalla Pro National Bank come data scientist, il tuo primo incarico consiste nel realizzare un modello in grado di stimare l'affidabilità creditizia di un clienti, al fine di di aiutare il team dedicato a comprendere se accettare o meno la richiesta per il rilascio della carta di credito.

A tal fine ti vengono consegnati i dati anonimizzati di clienti che hanno già ottenuto la carta di credito e lo stato del loro debito mensile. 

I dati sono organizzati in 2 file csv che possono essere scaricati da qui.

**application_record.csv**
|Feature name|Explanation|Remarks| 
|:---|:---|:---| 
|ID|Client number||
|CODE_GENDER|Gender||
|FLAG_OWN_CAR|Is there a car||
|FLAG_OWN_REALTY|Is there a property||
|CNT_CHILDREN|Number of children||
|AMT_INCOME_TOTAL|Annual income||
|NAME._INCOME_TYPE|Income category||
|NAME_EDUCATION_TYPE|Education level||
|NAME_FAMILY_STATUS|Marital status||
|NAME_HOUSING_TYPE|Way of living||
|DAYS_BIRTH|Birthday|Count backwards from current day (0), -1 means yesterday|
|DAYS_EMPLOYED|Start date of employment|Count backwards from current day(0). If positive, it means the person currently unemployed.|
|FLAG_MOBIL|Is there a mobile phone||
|FLAG_WORK_PHONE|Is there a work phone||
|FLAG_PHONE|Is there a phone||
|FLAG_EMAIL|Is there an email||
|OCCUPATION_TYPE|Occupation||
|CNT_FAM_MEMBERS|Family size||

**credit_record.csv**
|Feature name|Explanation|Remarks| 
|:---|:---|:---| 
|ID|Client number||
|MONTHS_BALANCE|Record month|The month of the extracted data is the starting point, backwards, 0 is the current month, -1 is the previous month, and so on|
|STATUS|Status|0: 1-29 days past due 1:30-59 days past due 2: 60-89 days overdue: 3:90-119 days overdue: 4:120-149 days overdue 5: overdue or bed debts, write-offs for more than 150 days C: paid off that month X:no loan for the month|

Il tuo modello deve essere in grado di fornire un'indicazione al team sull'approvare o meno la richiesta di carta di credito per un dato cliente.

## BONUS
Se ad un cliente viene negata la carta di credito, il team deve essere in grado di fornirgli una motivazione, questo vuol dire che il tuo modello deve fornire delle indicazioni facilmente interpretabili.

## NOTE
Come avrai notato manca una variabile target, non ti vogliamo dare indicazioni, sta a te capire come procedere. Qualora non riuscissi a venirne a capo chiedi pure una mano al tuo coach nella classe virtuale di Python su Discord.
