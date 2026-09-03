# Historial de versiones

La versión que está publicada se ve arriba de todo en la página y en el pie.

---

## v2.2 — 3 de septiembre de 2026

**Banda nueva: GUERRA DE SOPORTE (BP · SE · OL).** El playbook decía qué hacer cuando
el soporte está en peligro, pero no cómo se avisa, quién responde ni hasta dónde.

- **Gramática de calls: `ESTADO + CLASE`.** Tres estados y nada más — `FOCUS`, `LOCK`
  y `LIBRE`. Con dos reglas que importan: **stuneado se habla igual** (el stun traba
  al personaje, no a la boca) y **si el soporte no canta, la barra de vida lo canta**,
  así que nadie espera la call para reaccionar.
- **El soporte reporta estado, no da órdenes.** Un healer con tres encima no está para
  decidir qué hace la CP.
- **Escalada de tres niveles** con disparador y respuesta: FOCUS (se mueve el soporte,
  corta solo el guardián), LOCK o vida bajando (el PL rompe contacto y vuelve),
  y caída (ya no es peel, es salida; nadie resucita dentro del foco).
- **Guardianes asignados de antemano**: BH cuida al BP, BD al SE, y el OL se cuida solo
  por su propio rol — tira y retrocede.
- **El lado ofensivo**: contra una CP **desordenada**, el TH va directo al BP; contra
  una **ordenada** se mata al SE, porque sin su recharge el BP se queda sin MP y deja
  de curar solo. La señal para distinguirlas es dónde está su soporte respecto de su
  melee.
- **Regla del intercambio**: cortás el focus para salvar a tu soporte salvo que el suyo
  esté por caer. Un kill al 20% no vale tu Bishop; uno al 80% sí.

**Corrección importante.** El escenario 6 decía *"todos protegen BP / SE"*. Eso es el
anti-patrón: amontonarse convierte una muerte en cinco, junta a la CP para el AoE
enemigo y regala el frente. Ahora dice **corta el guardián y el resto sigue peleando**,
y la banda lo remata con una franja roja.

---

## v2.1 — 3 de septiembre de 2026

**Escenario 4 (arqueros vs magos): las clases, no puntos grises.**
Las dos formaciones ahora muestran PL, WL, GL, TH, BH, BD, OL, SE y BP con su color,
igual que el resto del playbook. Antes eran círculos grises sin identificar y no se
entendía quién estaba dónde.

- El lado **COMPACTO** muestra la formación apretada en 3×3, con el PL adelante al
  centro y el BP protegido en el medio de la última fila.
- El lado **ABIERTO** muestra la misma CP dispersa, y el radio de AoE dibujado encima
  agarra a **uno solo**. Ese es todo el argumento del escenario.

**Versionado.** La página lleva versión y fecha visibles, y el repo lleva tags.

---

## v2.0 — 3 de septiembre de 2026

Refinado completo después de una revisión del mapa.

**Errores corregidos**

- **Una sola flecha de salida** en los escenarios 3, 5 y 6. Antes el dibujo mostraba
  dos salidas mientras el texto decía "salir por un solo lado".
- **Escenario 1**: las flechas de avance ahora salen de nuestra formación hacia el
  enemigo. Antes salían del enemigo hacia nosotros.
- **Escenario 6**: la amenaza entra por atrás, contra BP y SE, que es lo que dice el
  título. Antes las flechas apuntaban al frente.
- **Cantidades coherentes** con los títulos: 1 CP = 9 enemigos, 3 CP = 27.
- **Leyenda unificada** y respetada en todos los diagramas: verde solo para avance
  propio, morado solo para salida.

**Estrategia agregada**

- **Banda de ENCARAMIENTO**: costado +20% de crítico, espalda +30% de crítico y +30%
  de chance de Blow, el escudo bloquea **solo de frente**, y Backstab 3% adelante
  contra 100% atrás. Con la aclaración de que los cuadrantes se miden desde donde
  mira el enemigo, y que Aegis le devuelve el bloqueo en 360°.
- El **TH pasa de "busca flanco" a "va a la espalda"**, y el escenario 2 lo dibuja.
- **Escenario 4 partido en dos**: contra arqueros, compacto y cerrar distancia;
  contra magos, abierto. Antes recomendaba compacto para los dos casos.
- **Escenario 5**: aparece el bloque aliado de otro clan y la prohibición de tirar
  AoE hacia él.
- **Regla de assist**: todos al target que llama el PL.
- **Umbral de bajas**: 3 bajas, salida obligatoria.
- **El costo de morir**: sin Noblesse a nivel 53, cada muerte cuesta todos los buffs.

**Diseño**

- Los seis diagramas dejan de ser el mismo dibujo repetido: cada uno muestra la
  respuesta de su escenario.
- Tipografía más grande y notas clave resaltadas.
- Los seis colores de acento decorativos se reemplazan por un chip de severidad
  (RUTINA / PRESIÓN / CRISIS) que sí codifica algo.
- Inter cargada de Google Fonts; antes estaba pedida en el CSS y no se cargaba.

---

## v1.0 — 3 de septiembre de 2026

Primera publicación. Seis escenarios con diagramas, referencia de clases, protocolo
de bajas, secuencia general de respuesta y reglas clave.
