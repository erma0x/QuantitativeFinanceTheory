#finanza 
Value at Risk (VAR)

#### Definizione
Il VaR fornisce una stima, con un certo grado di confidenza, delle dimensioni delle perdite di un portafoglio in un determinato periodo di tempo.

Il calcolo “standard” del VaR formula le seguenti ipotesi:

-   **Condizioni di mercato standard** – Il VaR non dovrebbe considerare gli eventi estremi o “risk tail”, piuttosto dovrebbe fornire l’aspettativa delle perdite durante la normale operatività zione normale “day per day”.
-   **Volatilità e correlazioni** – Il VaR richiede la volatilità delle attività in esame, nonché le rispettive correlazioni. Queste due quantità sono difficili da stimare e sono soggette a cambiamenti continui.
-   **Normalità dei resi** – il VaR, nella sua forma standard, presuppone che i rendimenti dell’asset o del portafoglio siano normalmente distribuiti. Ciò porta a calcoli analitici più semplici, ma approssima NON realisticamente per la maggior parte delle attività.

### Metodi di calcolo
-   il metodo varianza-covarianza, assumendo che i rendimenti sono sempre distribuiti secondo una normale);
    
-   il metodo Monte Carlo, dove i rendimenti futuri delle attività sono simulate in maniera più o meno casuale, dati alcuni parametri;
    
-   la simulazione storica, dove si assume che i rendimenti delle attività si distribuiranno come si sono distribuite in passato.


## Pros & cons
### vantaggi

-   Il VaR è molto semplice da calcolare per le singole attività, le strategie algoritmiche, i portafogli quantistici, gli hedge fund e anche per i desk bancari.
-   Il periodo di tempo associato al VaR può essere modificato per diverse strategie di trading che hanno orizzonti temporali diversi.
-   Differenti valori del VaR possono essere associati a diverse forme di rischio, per esempio suddivise per classi di asset o tipologie di strumento. Ciò rende facile interpretare, ad esempio, dove si concentra la maggior parte del rischio del portafoglio.
-   Le singole strategie possono essere limitate all’interno di interi portafogli in base al singolo VaR.
-   Il VaR è semplice da interpretare dagli investitori e dei gestori di fondi esterni (potenzialmente) non tecnici.

### svantaggi
-   Il VaR non quantifica l’entità della perdita attesa oltre al valore del VaR, cioè valuta la probabilità di avere una perdita superiore ad uno specifico valore, ma non di quanto superi questo valore.
-   Non tiene conto di eventi estremi, ma solo delle condizioni tipiche di mercato.
-   Dal momento che utilizza i dati storici (è retrospettivo) non prenderà in considerazione i dati futuri del mercato che possono modificare le volatilità e le correlazioni tra gli asset.
-   Il VaR non deve essere usato in autonomia. Dovrebbe essere sempre utilizzato all’interno di una suite di tecniche per la gestione del rischio, come la diversificazione, l’allocazione ottimale del portafoglio e l’uso prudente della leva finanziaria.

