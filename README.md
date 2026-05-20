# Greedome

**Greedome** è un progetto homebrew per **Dungeons & Dragons 5.5Ed**, ambientato in un mondo industriale in cui magia, tecnologia, politica e capitale si scontrano e si contaminano.

Il progetto è scritto e mantenuto in **Obsidian**, usando una struttura modulare di file Markdown. Il materiale comprende ambientazione, classi, razze/specie, equipaggiamento, regole homebrew, tabelle, fazioni, luoghi, PNG e contenuti di supporto alla campagna.

---

## Stato del progetto

Il manuale è in fase di sviluppo attivo. I contenuti sono soggetti a revisione narrativa, meccanica e terminologica.

Priorità attuali:

1. revisione delle classi homebrew;
2. uniformazione della terminologia meccanica;
3. controllo della compatibilità con D&D 5.5Ed;
4. mantenimento della coerenza interna dell'ambientazione;
5. revisione progressiva di bilanciamento, leggibilità e riferimenti incrociati.

---

## Filosofia di design

Greedome non è una semplice trasposizione fantasy-industriale. Le classi, le regole e il tono dell'ambientazione devono riflettere un mondo in cui:

- la magia è una forza antica, instabile e politicizzata;
- la tecnologia è potere sociale, militare ed economico;
- le classi non sono solo pacchetti meccanici, ma ruoli riconoscibili dentro la società;
- alcune opzioni sono volutamente più rischiose, stigmatizzate o socialmente problematiche;
- il bilanciamento non è solo numerico, ma anche narrativo, sociale e situazionale.

Esempi:

- la **Strega** segue linee guida e codici di appartenenza simili, per funzione, ai vincoli morali del Paladino;
- il **Glitch** è volutamente più potente della media, ma compensato dal fatto di essere un outcast perseguitato, costretto a nascondere la propria natura;
- classi come **Inventore**, **Pistolero**, **Croupier** e **Ranger** rappresentano il rapporto specifico tra tecnica, guerra, rischio e sopravvivenza nel mondo di Greedome.

---

## Standard terminologico

Per mantenere coerenza nei file di classe e nelle regole homebrew, il progetto usa abbreviazioni italiane per caratteristiche e formule meccaniche.

### Caratteristiche

| Caratteristica | Abbreviazione |
| --- | --- |
| Forza | `FOR` |
| Destrezza | `DES` |
| Costituzione | `COS` |
| Intelligenza | `INT` |
| Saggezza | `SAG` |
| Carisma | `CAR` |

### Bonus di Competenza

Il **Bonus di Competenza** è abbreviato come:

```md
BC
```

### Modificatori

Formato standard:

```md
Mod FOR
Mod DES
Mod COS
Mod INT
Mod SAG
Mod CAR
```

### Tiri Salvezza

Formato standard:

```md
TS FOR
TS DES
TS COS
TS INT
TS SAG
TS CAR
```

### Formule ricorrenti

Esempi:

```md
BC/Riposo Lungo
BC/Riposo Breve
Mod INT/Riposo Lungo
Mod SAG/Riposo Breve
CD = 8 + Mod INT + BC
CD = 8 + Mod CAR + BC
```

Nel testo discorsivo si può usare la forma estesa quando migliora la leggibilità, ma nelle tabelle, nelle righe meccaniche e nelle formule si preferisce la forma abbreviata.

---

## Convenzioni meccaniche

Le sezioni meccaniche privilegiano formule brevi e leggibili.

Esempio:

```md
## Nome Privilegio (Livello)
**Azione Bonus • 9 m • BC/Riposo Lungo**
>Descrizione narrativa breve.

- Effetto meccanico.
- Limite o durata.
- Eventuale scaling.
```

Standard consigliati:

- `Azione`
- `Azione Bonus`
- `Reazione`
- `Passiva`
- `Riposo Breve`
- `Riposo Lungo`
- `Tiro per Colpire`
- `Tiro Salvezza`
- `Prova di Caratteristica`
- `Classe Armatura`
- `Punti Ferita`
- `Punti Ferita Temporanei`

---

## Compatibilità con D&D 5.5Ed

Il progetto usa D&D 5.5Ed come riferimento di base, ma contiene materiale homebrew esteso.

Quando una regola homebrew modifica o sostituisce una formulazione standard, deve essere scritta in modo esplicito.

Esempio importante:

```md
## Attacco Extra (5°)
**Passiva**
>Puoi attaccare due volte, anziché una, ogniqualvolta intraprendi l'Azione di Attacco nel tuo turno.
```

Non usare `Attacco Extra` per indicare una seconda azione completa. Se una classe ottiene realmente una seconda Azione, il privilegio deve avere un nome diverso e una descrizione separata.

---

## Workflow Obsidian

Il progetto è mantenuto in Obsidian. Plugin utilizzati:

- Advanced Tables;
- Editing Toolbar;
- Templater;
- Iconize;
- Mind Map.

I link interni usano la sintassi Obsidian:

```md
[[Nome File]]
```

Le tabelle, le liste di opzioni e i rimandi interni possono essere distribuiti in file separati quando questo migliora leggibilità e manutenzione.

---

## Note di manutenzione

Questa repository può contenere materiale in lavorazione, bozze, appunti e contenuti non ancora bilanciati.

Prima di considerare una sezione come definitiva, controllare:

1. coerenza terminologica;
2. chiarezza delle risorse e degli usi per riposo;
3. compatibilità con la struttura di azioni della 5.5Ed;
4. coerenza narrativa con Greedome;
5. eventuali rimandi Obsidian rotti o duplicati.

---

## Proprietà intellettuale

Greedome è un progetto homebrew privato. Tutti i contenuti originali dell'ambientazione, salvo materiale espressamente derivato da D&D o da fonti di riferimento, appartengono all'autore del progetto.

Dungeons & Dragons è proprietà dei rispettivi titolari. Questo progetto è materiale fan-made/homebrew e non è un prodotto ufficiale.
