# Kalas på spåret

Frågesport i På spåret-stil för tre lag. Programledaren visar spelet på TV:n, och lagen drar i nödbromsen från sina telefoner genom att skanna en QR-kod. Ingen app eller inloggning behövs.

## Köra lokalt

```
npm start
```

Öppna sedan http://localhost:3000.

## Railway

Koppla repot till ett nytt Railway-projekt. Railway känner igen Node-projektet och kör `npm start`. Under Settings → Networking, klicka på **Generate Domain** för att få en publik adress.

## Ändra frågor

Resor och frågor ligger i `PROGRAM` högst upp i skriptet i `index.html`. Skisserna i mellanrundan Skissen ligger i `SKISSER` och kommer från PartyParty.
