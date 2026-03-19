# Anton-Coin-Guide
Ein Guide von Benjamin

## 📱 Nutzung auf iOS oder Android
1. Installiere einen Browser mit Entwicklerwerkzeugen (z. B. Eruda Browser).
2. Öffne die Seite **anton.app**.
3. Logge dich in dein Konto ein.
4. Öffne die Entwicklerkonsole, und gebe dieses Skript ein. Ersteze HIERANZAHLEINFÜGEN durch die Menge Münzen die du haben willst. Wenn ein Fehler kommt oder es nicht funktioniert versuche es nochmal oder verkleinere die Münz Zahl.

## 🖥️ Nutzung auf dem PC
1. Öffne Google Chrome.
2. Navigiere zu **anton.app**.
3. Öffne die Entwicklerkonsole mit:
   - **F12** oder  
   - **Strg + Shift + I**
4. Gebe dieses Skript ein. Ersteze HIERANZAHLEINFÜGEN durch die Menge Münzen die du haben willst. Wenn ein Fehler kommt oder es nicht funktioniert versuche es nochmal oder verkleinere die Münz Zahl.

## Skript ##
```
addCoins = function(amount) {
        return typeof log != 'undefined' && log !== null ? log.log({
            event: "adjustCoins",
            value: amount
        }) : void 8;
    };
addCoins(HIERANZAHLEINFÜGEN)
```


## 💡 Hinweis
Bitte beachte die Nutzungsbedingungen der jeweiligen Plattform.
