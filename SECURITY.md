<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/msworks-it/.github/main/profile/assets/logo-mark-white.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/msworks-it/.github/main/profile/assets/logo-mark-dark.svg">
  <img alt="M's Works" src="https://raw.githubusercontent.com/msworks-it/.github/main/profile/assets/logo-mark-dark.svg" height="36">
</picture>

# Segnalare una vulnerabilità

Facciamo security audit e penetration test per mestiere. Prendiamo sul serio le segnalazioni che
arrivano a noi, e trattiamo chi le manda come tratteremmo un collega.

**Non aprire una issue pubblica per una vulnerabilità.** Scrivi a
**[antonio.murabito@msworks.it](mailto:antonio.murabito@msworks.it)**.

---

## Cosa copre questa policy

- I repository pubblici dell'organizzazione [msworks-it](https://github.com/msworks-it).
- I servizi che gestiamo sotto il dominio `msworks.it` e i suoi sottodomini.

Per i sistemi dei nostri clienti non possiamo autorizzare noi i test: scrivici comunque, giriamo la
segnalazione a chi di dovere e ti mettiamo in contatto.

## Cosa scrivere nella segnalazione

Quanto basta per riprodurre il problema:

- dove si trova (repository e file, oppure URL ed endpoint);
- che tipo di problema è, e cosa permette di fare a chi lo sfrutta;
- i passi per riprodurlo, o una proof of concept;
- se ti fa comodo, la tua idea su come sistemarlo.

Va benissimo anche una segnalazione imperfetta. Meglio una mail approssimativa oggi che una perfetta
mai.

## Cosa facciamo noi

| Quando | Cosa |
|---|---|
| Entro **3 giorni lavorativi** | Ti confermiamo di aver ricevuto la segnalazione. |
| Entro **10 giorni lavorativi** | Ti diciamo se l'abbiamo confermata, come la classifichiamo e che tempi prevediamo. |
| Alla chiusura | Ti avvisiamo del rilascio della correzione. |

Se vuoi essere citato come autore della scoperta, diccelo: lo facciamo volentieri. Se preferisci
restare anonimo, altrettanto volentieri.

Pubblichiamo i dettagli tecnici dopo che la correzione è disponibile, di norma entro **90 giorni**
dalla segnalazione. Se serve più tempo per motivi seri te lo spieghiamo, non lo decidiamo da soli.

## Le regole del gioco

Se resti dentro questi limiti, la tua ricerca è benvenuta e **non intraprenderemo azioni legali nei
tuoi confronti**:

- non accedere, modificare o esfiltrare dati che non siano tuoi — se ti imbatti in dati altrui,
  fermati e dillo nella segnalazione;
- niente attacchi di tipo denial of service, né test di carico;
- niente spam, phishing o social engineering verso persone, clienti o fornitori;
- non degradare il servizio per gli altri utenti;
- dacci un tempo ragionevole per correggere prima di rendere pubblico il problema.

Quello che sta fuori da questi limiti non è ricerca: è un attacco, e lo trattiamo come tale.

## Cosa di solito non consideriamo una vulnerabilità

Output grezzo di uno scanner senza impatto dimostrato, header di sicurezza mancanti senza uno
scenario di sfruttamento, versioni di librerie segnalate come vecchie ma non sfruttabili nel nostro
contesto, self-XSS, user enumeration su form di login pubblici, mancanza di rate limiting dove non
produce un danno concreto.

Se pensi che nel nostro caso specifico una di queste sia davvero sfruttabile, dimostracelo: cambiamo
idea volentieri di fronte a una proof of concept.

---

## Reporting a vulnerability (English)

**Please do not open a public issue.** Email
**[antonio.murabito@msworks.it](mailto:antonio.murabito@msworks.it)** — in English or Italian, both
are fine.

Include where the issue is, what it allows an attacker to do, and how to reproduce it. We acknowledge
within **3 working days**, triage within **10 working days**, and coordinate public
disclosure within **90 days** of the report. Credit is given if you want it.

Stay within the rules above — no access to other people's data, no DoS, no social engineering, no
service degradation, and give us reasonable time to fix — and we will not pursue legal action against
your research.
