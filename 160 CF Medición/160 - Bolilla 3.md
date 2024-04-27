# Bolilla 3: Estados Contables Ajustados por Inflación

## Introducción

Entre los activos y pasivos tenemos dos grupos:

- **Monetarios**: Son aquellos que, ante la inflación, han quedado expuestos, es decir, ganaron o perdieron poder adquisitivo, motivo por el cual no se ajustan por inflación, pero sí generan un REI o un RECPAM. Por ejemplo: _Caja y Bancos, Créditos, Documentos a cobrar, Proveedores_, todos siempre y cuando no tengan cláusulas de ajuste por inflación.
- **No Monetarios**: Estos, al no tener sus componentes expresados en pesos, sino en unidades físicas, deben ser reexpresados a la unidad monetaria para poder expresarlos en los Estados Contables. Si bien no están expuestos a la inflación, sí se ajustan por ella, debido a que la conversión a la unidad monetaria se hace a la fecha de incorporación del bien al Patrimonio Neto, y luego, ya sea al momento de cierre o a la valuación, la cantidad monetaria que representa el valor del bien, bajo un contexto inflacionario, habrá sufrido variaciones. Por ejemplo: _Bienes de Cambio, Bienes de Uso, Inversiones (excepto el Plazo Fijo), cuentas de Resultados, y cuentas de Patrimonio Neto_.

## Pasos para ajustar por inflación

1. **Determinar la fecha de origen**: **En el caso de los bienes**, será su fecha de incorporación al Patrimonio de la empresa. **En el caso de las cuentas del Estado de Resultados**, será al momento de su devengamiento en la mayoría de los casos, con algunas excepciones, como el _Costo de Mercadería Vendida_, que se harán a la fecha de incorporación de la mercadería que se vendió. En el caso de los _Resultados de Venta_, debido a que tienen dentro de sus componentes un _precio de venta_ y un _Valor de Origen_ de distintos momentos, se deberá tener en cuenta que, para el _precio de venta_, la fecha de origen será el momento de la venta, mientras que para el _Valor de Origen_, lo será la fecha de incorporación del bienes al Patrimonio del ente.
2. **Determinación del coeficiente de ajuste**: En base a los índices de precios del INDEC, se obtiene el coeficiente como la relación entre el _IPC a la fecha de cierre_ sobre el _IPC a la fecha de origen_: **IPFC / IPFO = COEFICIENTE**.
3. **Obtener el valor reexpresado**: Se multiplica el saldo histórico del bien por el coeficiente obtenido en el punto anterior, obteniéndose el _Valor reexpresado_.

## El Resultado por Exposición a la Inflación

El _REI_ será el resultado de la diferencia entre el _Valor de Origen_, indicado como **VH**, y el _Valor Reexpresado_, indicado como **VHrx**.

## Método del Capital Monetario

Este es un método para determinar el saldo final del REI y confirmar si se hizo bien el trabajo. El proceso para realizarlo es el siguiente:

1. **Determinar el capital monetario al inicio _CMi_**: Se lo obtiene como la diferencia entre el _Activo Monetario_ y el _Pasivo Monetario_. Si _AMi > PMi_, entonces el REI será negativo, mientras que si _AMi < PMi_, entonces el REI será positivo.
2. **Trabajamos con las operaciones del ejercicio**: Dentro del Libro Diario General, podemos tener _Operaciones Monetarias_, tales como depositos en banco, pagos, cobros, entre otras; _Operaciones No Monetarias_, tales como la determinación del CMV, distribuciones de dividendos en acciones, operaciones que no afectan al capital monetario; o bien _Operaciones Mixtas_, también llamadas _t1_, tales como compra de bienes y servicios, distribución de dividendos en efectivo, ventas, pagos, etc. Solo nos interesan, para esta operativa, las Operaciones Mixtas.

En esta operativa, debemos ir armando un cuadro tal que así:

| F.O.       | Concepto         | $    | t. interes | REI  |
| ---------- | ---------------- | ---- | ---------- | ---- |
| 01/01/X1   | CMi = 1000 - 300 | 700  | 0.3        | -210 |
| Mayo       | Dism. de Caja    | 1000 | 0.25       | 250  |
| Septiembre | Aum. de Clientes | 2500 | 0.1        | -250 |

En este cuadro, solo se registra la cuenta monetaria de las operaciones _t1_.

3. Al terminar de colocar las t1 en el cuadro, se totalizan las columnas monetarias y se obtiene el saldo del REI.

## Método del Proceso Secuencial

Tiene la misma función que el método anterior. Los pasos para realizarlo son estos:

1. Determinar _Activo Inicial_ (Ai) y _Pasivo Inicial_ (Pi) en moneda homogénea.
2. Determinar el _Patrimonio Neto Inicial_ (PNi) en moneda homogénea, por diferencia entre Ai y Pi.
3. Calcular _Activo al Cierre_ (Af) y _Pasivo al Cierre_ (Pf) en moneda homogénea.
4. Determinar el _Patrimonio Neto al Cierre_ (PNf) en moneda homogénea, por diferencia entre Af y Pf.
5. Llegar al _PNf_ ajustando sus componentes sin tener el _Resultado del Ejercicio_: **Capital + Aj. Cap. + RNA + Reservas = PNf sin R.E.**, todo en moneda homogénea.
6. Obtener el _Resultado del ejercicio_ haciendo **Punto 4 - Punto 5**.
7. Llegar al Resultado del Ejercicio por el Estado de Resultados completo, sin REI, todo ajustado.
8. Obtener el REI haciendo **Punto 6 - Punto 7**.
