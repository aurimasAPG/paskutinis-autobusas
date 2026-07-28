# Peace Music Freedom 2026 — „Paskutinis autobusas“

Paramos kampanijos puslapis. 43 Charkivo valstybinio muzikos licėjaus vaikai,
2026 m. rugpjūčio 31 – rugsėjo 14 d. Lietuvoje.

Organizuoja Vilniaus International Rotary klubas kartu su
Rotary Club Kharkiv-City ir Rotary apygarda 1462.

## Atnaujinimas

Visi kintantys skaičiai skaičiuojami iš vienos konstantos `index.html` apačioje:

```js
const RAISED = 16550;   // bendra surinkta suma eurais
```

Pakeitus ją persiskaičiuoja: tuščių vietų skaičius hero sekcijoje, užpildytos
vietos autobuse, dienų juosta, progreso juosta ir eilutė „liko N mecenatų“.

Rėmėjų vardai — `SEAT_NAMES`, `DAY_NAMES` ir `SUPPORTERS` masyvuose ten pat.
Vardai skelbiami tik gavus rėmėjo sutikimą.
