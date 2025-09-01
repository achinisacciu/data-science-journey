## Formule per le Distribuzioni di Frequenza

Quando si analizzano dati grezzi, è necessario organizzarli in tabelle di distribuzione di frequenza per poterli interpretare. La creazione di queste tabelle, specialmente per variabili continue, segue alcune formule pratiche per determinare il numero e l'ampiezza delle classi.

---

### 1. Calcolo del Campo di Variazione (R)

Il primo passo è calcolare il **campo di variazione** (o *range*), che rappresenta la differenza tra il valore massimo e il valore minimo osservato nei dati.

La formula è:
$$R = \text{Valore massimo} - \text{Valore minimo}$$
Ad esempio, con dati compresi tra 6.2 e 31.8, il calcolo è:
$$R = 31.8 - 6.2 = 25.6$$

---

### 2. Scelta del Numero di Classi (k)

Determinare il numero giusto di classi è fondamentale: troppe classi rendono la tabella poco leggibile, mentre troppo poche la rendono poco significativa. Il testo suggerisce due regole pratiche.

**Regola della Radice Quadrata**: Una regola semplice consiste nello scegliere un numero di classi (k) approssimativamente uguale alla radice quadrata del numero totale di dati (n).
    $$k \cong \sqrt{n}$$
**Formula di Sturges**: Un'altra regola, più specifica, utilizza il logaritmo in base 10 del numero dei dati (n).
    $$k \cong 1 + 3.322 \cdot \log_{10}n$$

Ad esempio, per 80 dati, la formula di Sturges suggerisce circa 7 classi.

---

### 3. Calcolo dell'Ampiezza delle Classi (a)

Una volta stabiliti il campo di variazione (R) e il numero di classi (k), si può determinare l'ampiezza di ciascuna classe (nel caso si scelgano classi di uguale ampiezza).

La formula è:
$$a \cong \frac{R}{k}$$

Riprendendo gli esempi precedenti, con $R=25.6$ e $k=7$, l'ampiezza risulta:
$$a = \frac{25.6}{7} \cong 3.7$$
Questo risultato suggerisce di usare un'ampiezza di 4 per semplicità.

**Nota importante**: Queste formule forniscono indicazioni di massima e devono essere valutate a seconda del tipo di dati da trattare.

---

### 4. Formula per il Diagramma Circolare

Per rappresentare graficamente le frequenze percentuali, si può usare un diagramma circolare. In questo grafico, ogni classe è rappresentata da un settore circolare la cui ampiezza è proporzionale alla frequenza.

Per calcolare l'ampiezza in gradi (g) di un settore, conoscendo la sua frequenza percentuale (f), si usa la proporzione:
$$f : 100 = g : 360^{\circ}$$
