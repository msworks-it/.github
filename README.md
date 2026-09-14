# `.github` — M's Works

Repository di configurazione dell'organizzazione [**msworks-it**](https://github.com/msworks-it).

Non contiene codice applicativo: contiene il profilo pubblico dell'organizzazione e gli asset di
brand usati per renderizzarlo.

## Struttura

```
profile/
  README.md                  ← il README mostrato su github.com/msworks-it
  assets/
    banner-light.svg         banner per il tema chiaro di GitHub
    banner-dark.svg          banner per il tema scuro di GitHub
    logo-mark-dark.svg       marchio ufficiale, versione scura (fondo chiaro)
    logo-mark-white.svg      marchio ufficiale, versione chiara (fondo scuro)
    logo-lockup.svg          lockup completo marchio + logotipo
    logo-lockup-alt.svg      lockup alternativo
    montserrat-latin.woff2   Montserrat variabile, subset latin (SIL OFL 1.1)
```

## Brand

Palette e tipografia sono quelle del design system di [msworks.it](https://www.msworks.it) (DS v2).

| Token | Valore | Uso |
|---|---|---|
| `--ms-ink` | `#111111` | testo principale, fondo scuro |
| `--ms-red` | `#C60001` | unico accento del brand |
| `--ms-red-dark` | `#9E0001` | stato hover dell'accento |
| `--ms-slate` | `#54575A` | testo secondario |
| `--ms-surface` | `#F5F5F3` | superfici |
| `--ms-line` | `#E3E3E1` | filetti e bordi |
| `--ms-paper` | `#FFFFFF` | fondo chiaro |

Tipografia: **Montserrat** (400 / 700 / 800 / 900). Spigoli netti, `radius: 0`.

## Rigenerare i banner

I due banner sono SVG generati: incorporano il marchio ufficiale e il font Montserrat come
`@font-face` in base64, così restano identici ovunque senza dipendere da font esterni (GitHub non
carica risorse di terze parti dentro le immagini).

Per modificarli si edita direttamente l'SVG: testo, colori e posizioni sono leggibili in chiaro in
testa al file, il blob base64 del font è l'unica parte da non toccare.

## Come GitHub usa questo repository

GitHub mostra `profile/README.md` sulla pagina pubblica dell'organizzazione. Il repository deve
chiamarsi esattamente `.github` ed essere pubblico. Qui possono essere aggiunti anche i file di
community condivisi da tutti i repo dell'organizzazione (`CONTRIBUTING.md`, `SECURITY.md`,
`ISSUE_TEMPLATE/`, `PULL_REQUEST_TEMPLATE.md`).
