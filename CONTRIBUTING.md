<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/msworks-it/.github/main/profile/assets/logo-mark-white.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/msworks-it/.github/main/profile/assets/logo-mark-dark.svg">
  <img alt="M's Works" src="https://raw.githubusercontent.com/msworks-it/.github/main/profile/assets/logo-mark-dark.svg" height="36">
</picture>

# Contribuire

Grazie per l'interesse. Qui trovi come lavoriamo sui repository pubblici di
[msworks-it](https://github.com/msworks-it).

<sub>Italiano o inglese, scegli tu: rispondiamo in entrambe le lingue.<br>
<i>Italian or English, whichever you prefer — we answer in both.</i></sub>

---

## Prima di aprire qualcosa

**Hai trovato un bug?** Apri una issue e descrivi cosa ti aspettavi e cosa è successo davvero. I due
pezzi che servono sempre sono i passi per riprodurlo e la versione che stavi usando.

**Hai un'idea?** Apri una issue e raccontaci il problema che risolve, non solo la soluzione che hai in
mente. Il problema è la parte che ci serve per capire se e come farlo.

**Hai trovato una vulnerabilità?** Non aprire una issue: leggi
[SECURITY.md](https://github.com/msworks-it/.github/blob/main/SECURITY.md).

**Sei un cliente con una richiesta sul tuo progetto?** GitHub non è il canale giusto, vedi
[SUPPORT.md](https://github.com/msworks-it/.github/blob/main/SUPPORT.md).

Prima di scrivere, un'occhiata alle issue già aperte: se la tua c'è già, aggiungici il tuo caso
invece di aprirne una nuova. Due segnalazioni dello stesso problema con dettagli diversi valgono meno
di una sola che li contiene entrambi.

## Aprire una pull request

1. Se il cambiamento non è banale, **apri prima una issue**. Serve a non farti scrivere codice che poi
   non possiamo accettare — è una cortesia verso di te, non un ostacolo.
2. Forka, e lavora su un branch dedicato.
3. Ogni repository ha il suo `README.md`: lì trovi come installare le dipendenze, far girare i test e
   avviare il progetto in locale. Le istruzioni valide sono quelle, non queste.
4. Prima di aprire la PR: i test passano, il linter è pulito, il progetto compila.

### Cosa rende una PR facile da accettare

- **Una cosa sola per PR.** Una correzione e un refactor nello stesso diff diventano una PR che non
  possiamo né approvare né rifiutare per intero.
- **Spiega il perché, non il cosa.** Il cosa lo leggiamo dal diff. Il perché no.
- **Tocca solo quello che serve.** Riformattazioni di massa, cambi di stile e aggiornamenti di
  dipendenze non richiesti vanno in PR separate.
- **Se cambia l'uso, aggiorna il README.** Documentazione e codice che divergono sono un bug che si
  manifesta più tardi.
- **Niente segreti nel diff.** Chiavi, token, `.env`, dump di dati reali: mai. Se ti scappa, dillo
  subito — una chiave pubblicata va revocata, non solo rimossa dal commit.

### Commit

Messaggi all'imperativo, che dicono cosa fa il commit: `aggiungi rate limit sul login`,
`correggi calcolo IVA su note di credito`. Italiano o inglese, purché coerente dentro lo stesso
repository.

## Revisione

Guardiamo le PR quando possiamo: siamo uno studio piccolo, non un progetto con manutentori a tempo
pieno. Se dopo due settimane non hai ricevuto risposta, scrivi un commento sulla PR per farla
risalire — non è maleducazione, è utile.

Una richiesta di modifica in review riguarda il codice, non chi l'ha scritto. E vale anche al
contrario: se non sei d'accordo con un nostro commento, dillo e discutiamone.

## Licenza

Aprendo una pull request accetti che il tuo contributo sia distribuito con la stessa licenza del
repository su cui stai lavorando. La licenza è nel file `LICENSE` di ogni repo.
