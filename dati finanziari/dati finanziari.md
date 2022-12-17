#finanza

#### Security master database
solitamente nei gruppi di finanza quantitativa si ha a disposizione un database centrale che contiene dati storici di tutti gli strumenti finanziari vogliamo analizzare

### Dati fondamentali
I dati fondamentali sono spesso riportati su base settimanale, mensile, trimestrale o anche annuale. Tali dati includono dati sui salari, report sulle prestazioni dei fondi hedge, depositi SEC, indici basati sull’inflazione (come l’indice dei prezzi al consumo), la crescita economica e i conti aziendali.

##### Storage dei dati fondamentali
Richiedono spesso l'utilizzo di Database non strutturati come mongoDB. L’alternativa è archiviare il testo di file flat in un RDBMS, che è meno appropriato, dal momento che le interrogazioni full-text sono più complicate.

