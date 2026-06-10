# Screenshots — stato

✅ Già presenti:
- `01_map.jpg` — mappa (zona San Benedetto; DA SOSTITUIRE con versione su Bologna, vedi sotto)
- `04_profile_gamification.jpg` — profilo con livelli/XP/badge ✔ definitivo

❌ Mancanti — da catturare **con posizione simulata su Bologna centro** (dove ci sono i volantini e le 623k offerte; a San Benedetto l'app è vuota):
- `02_flyer_deck.jpg` — deck copertine volantini ("Sfoglia offerte")
- `03_offer_swipe.jpg` — card offerta con prodotto e prezzo ben visibili
- `01_map.jpg` (ri-cattura) — mappa con pin dei negozi e conteggi offerte

## Come simulare la posizione su Bologna

**Opzione A — sul telefono (S24):** Impostazioni → Opzioni sviluppatore → "Seleziona app posizione fittizia" → installare un'app tipo "Fake GPS Location" dal Play Store → impostare Bologna centro (44.494, 11.343) → aprire Huntly.

**Opzione B — emulatore Android Studio:** ⋮ Extended controls → Location → cercare Bologna → Set location → avviare l'app.

Dopo la cattura: copiare qui i file con i nomi esatti, poi:
```
git add assets && git commit -m "Add app screenshots" && git push
```
Questo file si può cancellare quando gli screenshot sono completi.
