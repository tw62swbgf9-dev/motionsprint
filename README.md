# MotionSprint 1.0

Web app PWA indipendente per allenare la pianificazione spaziale con puzzle originali ispirati alla tipologia *motionChallenge*. Non è un prodotto Aon e non riproduce il suo algoritmo proprietario.

## Funzionalità

- **Allenamento**: 10 puzzle al livello selezionato, senza tempo, con possibilità di riprovare.
- **Sfida**: 5 minuti, nuovi puzzle senza limite prefissato, difficoltà che sale dopo ogni 3 puzzle risolti.
- **Simulazione**: 6 minuti (durata indicata dalla documentazione pubblica Aon per motionChallenge).
- Controlli touch: trascina pallina/blocchi; in alternativa tocca un elemento e usa le frecce, scegliendo 1, 2, 3 caselle o fino all'ostacolo.
- Conteggio mosse, minimo matematico certificato tramite ricerca esaustiva su ogni puzzle, numero risolti e saltati, riepilogo e cronologia locale.
- 52 puzzle originali verificati, con selezione casuale e rotazione per livello; ogni sessione ricampiona il gruppo.
- Funziona offline dopo la prima visita online in browser compatibile.

## Pubblicazione su GitHub Pages

Carica tutti i file di questa cartella **alla radice** di un repository pubblico (ad esempio `motionsprint`), quindi Settings → Pages → Deploy from a branch → `main` e `/ (root)`. Visita `https://TUO-UTENTE.github.io/motionsprint/` dal tablet Huawei o dal PC. Puoi usare un repository distinto da EquaSprint oppure mettere questa cartella in una sottocartella di un repository già esistente. In tal caso il percorso per l'app cambia di conseguenza.

## Regole della simulazione

La pallina e i blocchi possono scorrere orizzontalmente o verticalmente, senza sovrapporsi a muri o altri pezzi. Ciascun trascinamento su una linea retta conta una mossa, a prescindere dalle caselle percorse. Non si ruotano i blocchi. Il gioco è completato quando la pallina entra nella casella verde di uscita. I livelli hanno dimensioni, ostacoli e minimi crescenti. Le regole esatte e i punteggi dell'assessment ufficiale non sono pubblicati: questo è un esercizio indipendente.

**Nota tecnica**: trascinando su touchscreen, uno spostamento di meno di metà cella può essere arrotondato a una cella; l'alternativa con pulsanti è disponibile per precisione.
