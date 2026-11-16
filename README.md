# VAR_INLFACION_COLOMBIA_USA
Pronóstico de la inflación de Colombia con un VAR usando la inflación de EE.UU.

## ¿Qué hice?
- Datos de FRED (2001-2026)
- Pruebas ADF y KPSS: ambas series estacionarias
- Selección de rezagos: AIC = 13, BIC = 2
- Estimación VAR(13)
- Diagnósticos: Sin autocorrelación, no normalidad y efectos ARCH
- Pronóstico 24 meses

## Resultados clave
- R2 Colombia: 0.70
- R2 EE.UU.: 0.36
- EE.UU. Granger-causa a Colombia
- Coeficiente L1.infUSA = 0.12: si EE.UU. sube 1%, Colombia sube 0.12% al mes siguiente
