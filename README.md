# MotorNow F1 · feed público de clasificación

Este repositorio contiene exclusivamente datos de clasificación destinados a la web MotorNow.

- `standings.json`: **previsualización no oficial** de F1 2026, basada en los puntos del campeonato principal y los 119 puntos comprobados de México.
- `status: PREVIEW_NOT_OFFICIAL` y `publishable: false` significan que el archivo **no constituye una clasificación oficialmente publicada**.
- El JSON puede consultarse desde WordPress sin credenciales en:
  `https://raw.githubusercontent.com/MotorNowRacing/motornow-f1-feed/main/standings.json`.

El código de cálculo, los historiales y las auditorías se conservan en un repositorio privado. Este repositorio público no debe contener contraseñas, tokens ni archivos de acceso al servidor.

**Estado de sincronización:** se requiere configurar en el repositorio privado un secreto de GitHub Actions `F1_FEED_PUSH_TOKEN` con acceso de escritura únicamente a `motornow-f1-feed`. Hasta entonces, `standings.json` es una copia pública estática, no un feed actualizado automáticamente.
