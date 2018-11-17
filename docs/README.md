<div align="center">
  <img src="/img/icons/icon.jpg" alt="Logo" width="140" height="140">
  <h1>Delta</h1>
  <p>📚 Een moderne versie van Magister, gemaakt voor leerlingen.</p>
  <a href="https://github.com/deltaproject/Delta/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/deltaproject/Delta.svg?style=flat-square" alt="Licentie"></img>
  </a>
  <a href="https://github.com/deltaproject/Delta/issues">
    <img src="https://img.shields.io/github/issues/deltaproject/Delta.svg?style=flat-square" alt="Issues"></img>
  </a>
  <a href="https://www.codefactor.io/repository/github/deltaproject/delta">
    <img src="https://www.codefactor.io/repository/github/deltaproject/delta/badge" alt="CodeFactor"></img>
  </a>
  <br><br>
</div>

# Installatie
Delta is momenteel nog in de bètafase, dus verdere instructies en documentatie volgen later.

# Voor ontwikkelaars
1. Clone deze repository naar je lokale schijf met `git clone https://github.com/deltaproject/Delta`
2. Open je Terminal-emulator en navigeer naar de locatie waar je de repository hebt gecloned
3. Typ `npm install` om alle dependencies te installeren
4. Bewerk vervolgens `main.js` met een teksteditor en verander de volgende variabelen:
```js
var m = new Magister.Magister({
    school: '<volledige schoolnaam>',
    username: '<gebruikersnaam>',
    password: '<wachtwoord>'
});
```
5. Start Delta met `electron .`

# Credits
Met speciale dank aan [Lieuwe Rooijakkers (@lieuwex)](https://github.com/lieuwex) voor het maken van [MagisterJS](https://github.com/simplyGits/MagisterJS), die Delta mogelijk maakte.

# Licentie
Delta is gelicentieerd onder een [Mozilla Public License 2.0](https://github.com/deltaproject/Delta/blob/master/LICENSE) licentie.
