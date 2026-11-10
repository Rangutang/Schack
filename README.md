# Schack

Kontors-Schack – autonom schackturnering i webbläsaren. En enda HTML-fil: `kontors-schack.html`.
Öppna filen i webbläsaren (gärna i helskärm, tangent `F`).

## Funktioner
- Kvalformat: gruppspel eller **schweizsystem** (växla med `T`, eller sätt `format: 'swiss'` i `CONFIG`), med ett antal omgångar och topp-N vidare till slutspel
- Slutspel i utslagsronder efter kvalet
- **Opening book** – partierna börjar med igenkännbara öppningar (t.ex. Spanskt parti, Sicilianskt, Damgambit)
- **Schackklocka per spelare** (2 minuter) – slut på tiden är förlust
- **Fokusbord**: när minst 4 partier spelas samtidigt får ett bord spotlight som växlar var 20:e sekund
- **Elo-rating** i mästerskapstabellen (start 1200, K-faktor 32), sparas mellan turneringar

## Tangenter
- `Mellanslag`/`P`: paus
- `M`: ljud av/på
- `N`: ändra deltagare
- `F`: helskärm
- `R`: ny turnering
- `T`: växla kvalformat (grupper ↔ schweiz)
- `S`: visa/dölj paneler
- `Ctrl+Shift+X`: nollställ mästerskapet
