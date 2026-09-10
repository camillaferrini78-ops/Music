# Ritornello — impara l'inglese con le canzoni

App web installabile (PWA) su Android, iPhone, Windows, Mac e Linux.

## Cosa fa
- **Cerca** un brano per titolo o artista (catalogo Apple/iTunes) e mostra **anno di uscita**, album e copertina.
- **Ascolta l'originale**: anteprima di 30 secondi integrata, più link diretti a YouTube, Spotify e Apple Music per il brano intero.
- **Testo recuperato automaticamente** dagli archivi aperti LRCLIB e lyrics.ovh, con **traduzione riga per riga** e **traduzione della singola parola con un tocco**, insieme a pronuncia, fonetica e definizione inglese.
- **Spiegazione del significato** della canzone, del contesto e delle espressioni idiomatiche.
- **Storico** di tutto quello che hai aperto, con i testi e le traduzioni già salvati.
- **Vocabolario** personale con ripasso a carte.
- **Riconoscimento audio**: registra 8 secondi di musica e trova il brano, come Shazam.

## Come installarla

### 1. Mettila online (una volta sola, gratis)
Il riconoscimento dal microfono e l'installazione richiedono HTTPS. Carica questa cartella su uno di questi servizi:
- **Netlify Drop** (netlify.com/drop): trascini la cartella nel browser, in 20 secondi hai un indirizzo.
- **GitHub Pages**: crea un repository, carica i file, attiva Pages dalle impostazioni.
- Qualsiasi hosting o NAS con HTTPS.

### 2. Installala
- **Android / Chrome**: apri l'indirizzo → menu ⋮ → *Installa app*.
- **iPhone / Safari**: apri l'indirizzo → tasto Condividi → *Aggiungi a Home*.
- **PC e Mac (Chrome o Edge)**: icona ⊕ nella barra degli indirizzi → *Installa*.

Per provarla subito senza hosting basta aprire `index.html` con doppio clic: funziona tutto tranne il microfono e l'installazione.

## Le due chiavi opzionali (Impostazioni)
| Serve per | Dove si prende | Costo |
|---|---|---|
| Riconoscere la canzone dal microfono | audd.io | prova gratuita, poi a consumo |
| Spiegazione del significato | console.anthropic.com | a consumo, pochi centesimi |

Ricerca, anteprime audio, traduzioni e vocabolario funzionano senza nessuna chiave.

## Come arrivano i testi
Aprendo un brano l'app cerca il testo da sola, in questo ordine:
1. **LRCLIB** con titolo, artista, album e durata (corrispondenza esatta);
2. **LRCLIB** in modalità ricerca, scegliendo il risultato più simile;
3. **lyrics.ovh** come seconda fonte.

Il testo trovato viene salvato sul dispositivo, così la seconda volta compare subito anche senza rete. Se nessuna fonte ce l'ha — succede con brani molto recenti o poco noti — resta il campo per incollarlo a mano e il link a Genius.

Se il testo non arriva mai e il pulsante *Cerca di nuovo* non basta, è il browser che blocca le richieste verso altri siti: in *Impostazioni* c'è un campo dove indicare un indirizzo ponte (per esempio `https://corsproxy.io/?`) che risolve il problema.

Questi archivi sono alimentati dalla comunità e i testi restano materiale protetto dal diritto d'autore: usali per studio personale. L'app non ne conserva copie sui propri server, semplicemente perché non ha server.

## Privacy
Storico, testi, traduzioni, vocabolario e chiavi restano nel browser del dispositivo. Nessun account, nessun server. Da *Impostazioni* puoi esportare un backup o cancellare tutto.
