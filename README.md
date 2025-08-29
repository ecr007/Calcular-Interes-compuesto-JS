```js
const capital_inicial = 20000;
const tasa = 0.07; // 5% anual
const años = 21;   // de 2004 a 2025

// Fórmula de interés compuesto
const monto_final = capital_inicial * Math.pow((1 + tasa), años);

console.log(monto_final);

```
