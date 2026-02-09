<p align="center">
  <img src="https://www.umimeto.org/asset/global/img/logo-umime.svg" alt="Umime logo" width="220" />
</p>

# Použití bota na Discordu

Bot slouží k přehlednému zobrazení správných odpovědí. Stačí použít jeden z příkazů níže a vložit obfuskovaný string, který se automaticky vloží jako `message.txt` kvůli character limitu discordu.
# Tutorial
- Načteme si stránku s úkoly
- Zapneme dev tools pomocí `F12` nebo `ctrl + shift + I`
- Navigujeme do záložky `Network`

<p>
  <img src="https://media.discordapp.net/attachments/1469747553661878453/1470491322296303800/image.png?ex=698b7d43&is=698a2bc3&hm=8cc598128372bec8874e5df2a71987f11916ff9f9ee306be3a911209f7ed0206&=&format=webp&quality=lossless" alt="tutorial-step-1" width="1000" />
</p>

- Načteme požadované cvičení
<p>
  <img src="https://media.discordapp.net/attachments/1469747553661878453/1470490648120524954/image.png?ex=698b7ca2&is=698a2b22&hm=0ecf6e84725bb8418e9e749a1917e3e5a81cedaa221cc7857b1430b612e1a132&=&format=webp&quality=lossless&width=1826&height=864" alt="tutorial-step-2" width="1000" />
</p>

- V tabu `Network` nás zajímá tento paket:
- vyznačuje se zeleným číslem `200` a `doplnovackaLoadQuestions...`
<p>
  <img src="https://media.discordapp.net/attachments/1469747553661878453/1470490965612564675/image.png?ex=698b7cee&is=698a2b6e&hm=601583da228ddf008f1bdf1e29f649a294a78d290be86d589c22d27a82bcf6d9&=&format=webp&quality=lossless" alt="tutorial-step-3" width="600" />
</p>

- Rozklikneme si tento paket a v tabu `Response` nás zajímá tento `string` (každý bude mít jedinečný string, z čehož vyplývá, že každý bude mít jiné pořadí otázek)
- Kopírujeme pomocí `CTRL + A` a následně `CTRL + C`
<p>
  <img src="https://media.discordapp.net/attachments/1469747553661878453/1470491733459730623/image.png?ex=698b7da5&is=698a2c25&hm=f73c14dc8c02394a20f15e228a73f51cfa3c5c2e916e338f501f790c5dfdeb87&=&format=webp&quality=lossless" alt="tutorial-step-4" width="600" />
</p>

- tento string dále použijeme s libovolným příkazem ve formátu `/příkaz (string, který se automaticky přiloží jako message.txt)`

# Příkazy

## `/rozhodovacka`

<p>
  <img src="https://media.discordapp.net/attachments/1469747553661878453/1469845182877929482/image.png?ex=69892380&is=6987d200&hm=94bada5fcb47fdf831dc3c636bb410dff584d4cb9841195096efb173bf1e0b76&=&format=webp&quality=lossless" alt="rozhodovacka" width="600" />
</p>

## `/serazovacka`

<p>
  <img src="https://media.discordapp.net/attachments/1469747553661878453/1469845382052708412/image.png?ex=698923af&is=6987d22f&hm=d22d3bbb33912058adaa9666f03abb6eb69a6ca6604d1b02a7ae808282986961&=&format=webp&quality=lossless" alt="serazovacka" width="600" />
</p>

## `/vpisovacka`

<p>
  <img src="https://media.discordapp.net/attachments/1469747553661878453/1469845098765353021/image.png?ex=6989236b&is=6987d1eb&hm=6775575ed94808e1d5c35025a99f45d8ce74569209d87df24454507208df910c&=&format=webp&quality=lossless" alt="vpisovacka" width="600" />
</p>

## Tipy

- Pokud příkazy nevidíš, napiš v kanálu `@bot sync`.
- Když dekódování selže, bot odpoví chybou.<p align="center">
