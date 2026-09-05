# living-poc — mirror de auditoría

Build del POC de living illustration de Lihué.

- Rama: `experience/poc-v3-signature`
- Commit: `18b8bfe9daf16d040cb11dadc81929a7fd979213`
  (baseline estabilizada: sin follaje derivado ni canvas de agua)
- Build: `vite build --base=/living-poc/`

Las rutas absolutas de assets se reescriben en el bundle generado a
`/living-poc/…`; el código fuente no se modifica.

## Cómo verlo

1. Espera unos segundos: el disparo está bloqueado hasta que el clip está
   precargado del todo.
2. Enciende el sonido (abajo a la derecha) antes de tocar nada.
3. Busca la pequeña luz en la hierba, a la derecha, y tócala.
4. El clip termina congelado en su último frame. Para repetir, recarga.

Mirror para revisión externa. El deploy oficial es
https://codeinstudio.dev/living-poc/ y sirve un commit anterior.
