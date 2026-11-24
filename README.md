# Stock de cajas

Aplicación web para controlar el stock de cajas sin sensores: el stock se calcula con los movimientos registrados.

**Stock actual = stock inicial + entradas − salidas ± ajustes por conteo**

## Funciones

- **Stock:** tarjetas por tipo de caja con cantidad actual, nivel y alerta **REPONER** al llegar al mínimo.
- **Registrar:** entradas y salidas con fecha, responsable y nota. No permite sacar más de lo que hay.
- **Movimientos:** historial con filtros por caja y tipo.
- **Conteo físico:** compara lo contado con el sistema y permite ajustar el stock.
- **Tipos de caja:** agregar y editar códigos, descripción, mínimo y stock inicial.

## Uso

Abre `index.html` en el navegador o publícalo con GitHub Pages (Settings → Pages → Branch `main` / root).

Los datos se guardan en el navegador (`localStorage`), así que quedan en el equipo y navegador donde se registran.
