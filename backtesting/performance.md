
#finanza 
### Trading performance
Calcolando le perfomance e confrontandole fra di loro, vogliamo verificare che:
-   Se le regole sistematiche codificate dalla strategia producono effettivamente un rendimento consistente e se la strategia possiede prestazioni positive nel backtesting.
-   Se una strategia mantiene questa prestazione positiva nel trading live o se deve essere fermata.
-   La capacità di confrontare più strategie / portafogli in modo tale da ridurre il rischio  associato all’assegnazione di una quantità limitata del capitale.


### Parametri per la performance
-   **Returns** – la percentuale di profitto rispetto al capitale iniziale. Le due principali misure di performance in questo ambito sono il _Total Return_ e il _Compound Annual Growth Rate (CAGR)_.

-   **Drawdowns** –  il DrawDown  rappresenta l’intensità della riduzione di valore del capitale in termini percentuali o assoluti, riferito ad un singolo ordine oppure all’intera strategia, e può essere definito come la differenza tra il massimo (picco) relativo e il successivo minimo (valle) relativo della curva equity di un portafoglio, quindi un calo di prestazioni della nostra strategia.

-   **Risk** – il rischio generalmente si riferisce sia al rischio di perdita di capitale, come ad esempio i drawndown, che alla volatilità dei returns (profitti). Quest’ultima solitamente viene calcolato tramite la deviazione standard annualizzata dei returns.

-   **Risk/Reward Ratio** – Il Rapporto Rischio / Rendimento rappresenta i profitti normalizzati rispetto al rischio. Poiché una maggiore volatilità può spesso generare maggiori rendimenti a scapito di maggiori drawdown, è fondamentale valutare quanto rischio viene assunto per unità di rendimento. Di conseguenza, è stata inventata una serie di indici e misure per quantificare questo aspetto delle prestazioni di una strategia, in particolare il _Shape Ratio_, il _Sortino Ratio_ e il _CALMAR Ratio_, tra gli altri. Inoltre _out of sample Sharpe_ è spesso la prima metrica che viene osservata quando si valuta le performance di una strategia.

-   **Trade Analysis** – le precedenti misure sono tutte applicabili sia alle _strategie_ che ai _portafogli_. Inoltre è utile osservare le prestazioni dei singoli trade ed esistono molte misure per caratterizzare le loro prestazioni. In particolare, è fondamentale quantificare il rapporto tra i trade vincenti / perdenti, l’_Average Profit per Trade_ e il _Win/Loss Ratio_.


### Trade analysis
È essenziale essere consapevoli della natura del profilo di trading della strategia e del proprio profilo psicologico. Potresti dover aprire e perdere tante piccole operazioni prima di vincerne una, e questo influisce sullo stress. 


### Statistiche riepilogative
-   **Total Proftt/Loss (PnL)** – Il PnL totale indica semplicemente se un particolare trade è stato proficuo o meno.
-   **Average Period PnL** – Il periodo medio di PnL indica se una barra, in media, genera un profitto o una perdita.
-   **Maximum Period Profit** – Indica il maggiore profitto per periodo di barra realizzato finora dal singolo trade. • 
-   **Maximum Period Loss** – Indica la maggiore perdita per periodo di barra realizzata finora dal singolo trade. Da notare che questo valore non dice nulla sulle future perdite del periodo! In futuro una perdita potrebbe essere anche molto più grande.
-   **Average Period Profit** – Indica la media della vita dei trade per tutti i  periodi in profitto.
-   **Average Period Loss** – Indica la media della vita dei trade per tutti i  periodi in perdita.
-   **Winning Periods** – Indica il totale di tutti i periodi in profitto.
-   **Losing Periods** – Indica il totale di tutti i periodi in perdita. 
-   **Percentage Win/Loss Periods** – Indica la percentuale di tutti i periodi vincenti rispetto ai periodi in perdita. Differisce notevolmente tra le strategie di tipo trend-following e mean-reverting.


link: Quadratic classifier
https://en.wikipedia.org/wiki/Quadratic_classifier#Quadratic_discriminant_analysis