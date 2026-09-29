# Pagina di screening

Pagina web per lo screening (titolo e abstract, full text), l'estrazione dei dati e il rischio di bias
delle systematic review di `sysrev-org`.

**Indirizzo**: `https://sysrev-org.github.io/screening/?repo=sysrev-org/NOME-DELLA-REVIEW`
(chi coordina manda il link completo ai revisori). La pagina si apre sulla panoramica delle fasi della review;
con `&stage=title_abstract`, `full_text`, `extraction` o `risk_of_bias` si apre direttamente una fase.

## Cosa contiene

Solo la pagina (`index.html`) e i suoi font (`fonts/`: Source Serif 4 e Source Sans 3 di Adobe, licenza SIL Open
Font License, testo in `fonts/LICENSE-*.md`): **nessun dato**. Record, decisioni e protocolli restano nei repository
privati delle review. La pagina li legge e li scrive direttamente dal browser, con il token GitHub di
chi la usa: il token resta nel browser e viene inviato soltanto a `api.github.com`. Con "Ricorda su questo
computer" la pagina tiene nel browser anche una copia dei file più grandi (come l'elenco dei record), per
aprirsi più in fretta; "Esci" la cancella.

Le istruzioni per i revisori sono nel file `guida-revisori.md` del repository di ciascuna review.

## Aggiornamenti

Questo repository viene aggiornato automaticamente dal repository del motore `sysrev`
(cartella `web/screening/`): non modificare i file qui, le modifiche verrebbero sovrascritte.
