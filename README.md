# Esercitazione del 13/06/23
### Creazione di una card (o 'Pin') di **Pinterest** partendo da un immagine di riferimento.
Tutti i comportamenti extra dei pulsanti sono stati applicati. Questa è la terza esercitazione realizzata per la seconda settimana di lezione del corso Web Development Part-time in Epicode. In questa cartella sono presenti tutti i file di progetto:

* La cartella assets contenente l'immagine usata come sfondo della card.
* Il file index.html con il codice HTML della pagina;
* Il file style.css con il codice CSS della pagina.

Per riprodurre il comportamento di **hover** con la comparsa/scomparsa degli elementi e l'inscurimento dell'immagine nello sfondo, sono stati creati tre livelli differenti ('layer','top' e 'bottom') seguendo questa struttura:

    <div class="card">
            <div class="layer">
                <div class="top"> Save </div>
                <div class="bottom"> Altri bottoni </div>
            </div>
    </div>
Ognuno di questi agisce in maniera differente per ricreare il movimento all'interno della card.