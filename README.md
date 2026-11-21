# El Camí de la X

Joc de plataformes per repassar l'**àlgebra de 2n d'ESO**. L'alumne recorre cinc mons, recull pistes amb la teoria i obre portes resolent exercicis d'expressions algebraiques i equacions.

**Juga-hi:** https://jjfortuny.github.io/matematiques-2eso/

Funciona al navegador, a l'ordinador i al mòbil, sense instal·lar res ni iniciar sessió.

## Continguts

Basat en el sentit algebraic del currículum de 2n d'ESO de la Generalitat de Catalunya.

| Món | Tema | Què s'hi treballa |
|---|---|---|
| 1 | Valor numèric | Substituir lletres per nombres, prioritat de les operacions, signes negatius, fórmules (perímetres, àrees, taxi, graus Fahrenheit) |
| 2 | Operacions algebraiques | Monomis i polinomis, suma i resta, producte de monomis, propietat distributiva, factor comú, identitats notables |
| 3 | Equacions | Equacions de primer grau sense parèntesis, transposició de termes, equacions amb parèntesis |
| 4 | Equacions amb denominadors | m.c.m. dels denominadors, signe menys davant d'una fracció, ordre de resolució |
| 5 | Problemes amb equacions | Nombres consecutius, edats, geometria, repartiments, diners, granges, angles d'un triangle |

## Com es juga

- **Moure's:** fletxes `←` `→` o `A` `D`. **Saltar:** `Espai` o `↑`. **Pausa:** `Esc`.
- Al mòbil apareixen botons a la pantalla.
- **Bombetes (pistes):** obren una fitxa de teoria amb un exemple pas a pas i una eina interactiva.
- **Portes vermelles:** cal resoldre un exercici per obrir-les. Si la resposta és incorrecta, es perd un cor i es mostra la resolució.
- **Blocs x:** saltant per sota s'obté un exercici extra que dona una estrella.
- Hi ha enemics (es poden trepitjar), punxes, monedes i punts de control.
- Si es fa servir la pista d'un exercici, la porta s'obre però no es guanya l'estrella.

## Exercicis

- Es **generen a l'atzar** cada vegada, així que es pot tornar a jugar un món amb exercicis diferents.
- Les equacions tenen sempre solució entera, i els problemes tenen dades coherents.
- Cada correcció mostra la **resolució pas a pas**: treure denominadors, treure parèntesis, transposar, reduir, aïllar i comprovar.
- Les respostes numèriques accepten enters, decimals amb coma o punt i fraccions (`-3`, `2,5`, `7/2`).
- Al món 2 les respostes són d'opció múltiple, i les opcions incorrectes reprodueixen errors típics (per exemple, `(x + 3)² = x² + 9`).

## Teoria interactiva

La **Biblioteca de pistes** permet consultar tota la teoria sense jugar. Inclou:

- Control lliscant per veure com canvia el valor numèric d'una expressió.
- Comparador de `x²`, `−x²` i `(−x)²`.
- Rectangle amb base i altura variables (perímetre i àrea).
- Parts d'un monomi (coeficient, part literal i grau).
- Agrupació de termes semblants.
- Model d'àrea per multiplicar polinomis i quadrat de `(a + b)²`.
- Balança animada per entendre les equacions.
- Calculadora del m.c.m. de denominadors.
- Targetes per traduir frases del català al llenguatge algebraic.

## Progrés

Les estrelles i els mons superats es desen al **navegador de cada alumne** (`localStorage`). Si es canvia d'ordinador, es fa servir la navegació privada o s'esborren les dades del navegador, el progrés torna a zero.

## Aspectes tècnics

- Un sol fitxer: [`index.html`](index.html), amb HTML, CSS i JavaScript, sense dependències (només les fonts de Google Fonts).
- El joc es dibuixa en un `canvas` i les fitxes de teoria i exercicis són HTML.
- S'adapta al tema clar o fosc del sistema: llibreta quadriculada en mode clar i pissarra en mode fosc.
- Publicat amb GitHub Pages des de la branca `main`.

Per provar-lo en local, n'hi ha prou d'obrir `index.html` amb el navegador.
