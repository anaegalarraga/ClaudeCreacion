# Revisión acuerdos Easy Chile HI 2025 – 11 proveedores

Criterios aplicados (los que indicaste):
- Se toma el último acuerdo firmado de la carpeta. Si no hay acuerdo 2025, rige el último firmado.
- Cuando hay más de un acuerdo, se aplican todos, cada uno a su alcance: Retail = Org. 2001, Mayorista = Org. 2002, y los surtidos parciales a su surtido.
- Compras: Importe Neto Entregado por Mes RealEM. Las entregas de 2026 de OC 2025 van a diciembre, igual que hace la web.
- PAGADO: VI_Debitos, Tipo "Acuerdo", con AñoLiq 2025. A eso se suman los faltantes del KSB1, cuando hay KSB1 en el archivo.

Todos los importes están en pesos chilenos.

## Resumen

| Proveedor | Saldo a reclamar | Conclusión | Excel |
|---|---:|---|---|
| 1000044 LEGRAND | 827.800 (Publicidad + Fijo; error puntual 719.723) | CON RECLAMO (BORRADOR) | Presentación armada (BORRADOR) |
| 1000071 HOFFENS | 108.581.846 (Pub+Fijo 33.349.405 · Escala 70.704.117 · B2B 4.528.324) | CON RECLAMO (BORRADOR) | Presentación armada (BORRADOR) |
| 1000104 LOUISIANA PACIFIC | No se puede calcular | PENDIENTE | – |
| 1000211 SAINT-GOBAIN WEBER | Todo negativo | SIN RECLAMO | OK (2 observaciones) |
| 1000730 NMC | 15.237.028 (Escala Crecimiento) | CON RECLAMO | **Corregido**: Escala MY en la Presentación y B2B fuera de secc. 13/43 · Presentación armada |
| 1001339 MADERAS ARAUCO | No se puede calcular | PENDIENTE | El 7% de Centralizada no tiene respaldo |
| 1003494 CINTAC | 4.224.268 (B2B) | CON RECLAMO | Presentación armada · escalas en toneladas pendientes |
| 4000006878 KNAUF | Neteo Pub+Fijo −22.173.522 (MY solo +4.765.074) | SIN RECLAMO | **Corregido**: fórmula de enero + entregas 2026 en diciembre |
| 4000008837 PIMARES | 19.724.595 (Escala Fija + Publicidad) | CON RECLAMO | **Corregido**: Escala Fija 3,5% · Escala Crecimiento no llega al primer tramo (validado por Ana) · Presentación armada |
| 4000008885 WMART | 874.607 (B2B) | CON RECLAMO | OK · Presentación armada |
| 4000008973 TAPIA Y ALVAREZ | −8.022.825 | RESULTADO NEGATIVO, analizado sin reclamo | OK |


## Actualización 08/10 (con tus respuestas)

- **NMC – OF-9514-2:** en la hoja AportesManuales, la referencia 37184713 dice **"Cobro escala 2025 NMC"** (15.197.335). Es el cobro de la Escala 2025, así que **se toma como PAGADO**, como lo había hecho Ana. Escala Crecimiento: DEBIDO 34.726.479 · PAGADO 19.489.451 · **DIF 15.237.028**. El Excel de NMC queda como en la versión anterior (Escala MY + B2B), sin reclasificar la OF.
- **Hoffens – criterio de Julián 2024:**
  - **Pub + Fijo:** CL5101 13%, CL5821 14%, CL5822 14%, CL5840 15% y Mayorista 5%. Escala Crecimiento 8% sobre todo REMA. B2B 0,15%.
  - **PAGADO:** los rebates se toman por el mes de la compra. El rebate de diciembre 2024 (cobrado en enero 2025) no cuenta. El de diciembre 2025 (cobrado el 30/01/2026, 19.578.357) sí. La "ESCALA 2024" (253 MM) es del año pasado.
  - **Escala 2025:** se toma el débito del 06/01/2026 por 170.806.471 (Desc.Obt.p/Volumen, igual que la "ESCALA 2024" de enero 2025).
  - **Resultado:**

    | Condición | DEBIDO | PAGADO | DIF |
    |---|---:|---:|---:|
    | Pub + Fijo | 381.183.427 | 347.834.022 | 33.349.405 |
    | Escala 8% | 241.510.588 | 170.806.471 | 70.704.117 |
    | B2B | 4.528.324 | 0 | 4.528.324 |

  - **Punto a validar:** el 31/03/2026 hay 77,9 MM de "Ingreso por publicidad" sin descripción (docs. ref. 37597518 y 37597521). En 2025 los "DIFERENCIAL 2024" se cobraron el 31/03, así que estos pueden ser los diferenciales 2025. Si lo son, Pub + Fijo y B2B podrían cerrar.
- **Cintac – criterio Julián 2024 y cláusula 15:**
  - **OC anteriores al 20/01/2025** (660,9 MM recibidos): llevan las condiciones 2024, Pub 3% + Fijo 7% + Escala 4% asegurada.
  - **OC desde el 20/01:** llevan el 2% de negociación extra (el 12% ya está en el precio).
  - **Grupo Pub + Fijo:** DEBIDO 203,2 MM contra PAGADO 214,4 MM (incluye aportes manuales "Bonificación Fija" por 112,4 MM). **Negativo**, sin reclamo.
  - **B2B:** se mantiene el reclamo de 4.224.268.
  - **Escalas en toneladas:** no se pueden calcular sin las toneladas. En 2024 Julián usó 2,25% Mayorista, así que tuvo el dato. Pagado de escala 2025: 131,9 MM (48,5 MM en dic-25 + 83,3 MM en ene-26). Si se alcanzaron los tramos máximos, la diferencia sería de unos +3,7 MM. Si no, da negativo.
- **B2B con piso UF:** apliqué el criterio del modelo Passol, mes a mes el mayor entre 1 UF y el 0,15%. En todos los casos con reclamo el 0,15% mensual supera la UF, así que no cambia nada.
- **LP = Louisiana Pacific (1000104):** en 2024 Julián tomó el "2% rapel mensual OSB-Protec" sobre una base de 1.821 MM, menos 7,5% de flete, sacada de la información comercial de LP. Para 2025 hace falta esa misma información comercial.
- **Verificación:** recalculé NMC, Knauf y Pimares con recálculo completo. NMC Escala DEBIDO 34.726.479, Knauf Publicidad DEBIDO 99.744.260. Coinciden con el informe.


## Comparación con 2024 (regla de Luciana: un error solo se corrige si cambió el acuerdo)

En 2024 los 11 proveedores quedaron "Analizado sin reclamo" en el ranking.

| Proveedor | ¿Cambió el AC 2024→2025? | ¿Error de 2024 repetido? | Error puntual 2025 |
|---|---|---|---|
| NMC | Sí: RT y MY nuevos (01/01/2025) | No. En 2024 la escala MY (3,5%) se cobró. | La Escala MY 2025 (4%) no se cobró por sistema. El "Cobro escala 2025 NMC" manual (15,2 MM) no alcanza: faltan 15.237.028. |
| Pimares | Sí: Fijo pasa de 2% a 3,5%; escala nueva | No. En 2024 el 2% se cobró completo. | (1) Ene–jul se siguió cobrando el 2% del AC 2024. (2) **Desde mediados de agosto no se cobra la Escala Fija** (sep, oct y nov en 0; dic 212.766). (3) La Escala Crecimiento no llega al primer tramo: no corresponde. |
| Cintac | Sí: RT, RT CL4321 y MY nuevos | Parcial. En 2024 el B2B se cobró desde junio ("se accedió a la plataforma en junio"). | B2B: el acuerdo 235102 solo liquidó enero (667.255). De febrero a diciembre no hay débitos. |
| WMART | Sí: AC REMA 2025 nuevo | **Sí.** En el ranking 2023 figura "Pendiente B2B UF. No tiene débitos". | El acuerdo 235010 tiene cargadas Z033 0,15% y Z034 1 UF (01.01–31.12.2025), pero **no tiene ninguna liquidación**. |
| Legrand | RT no (rige AC 2024); MY sí | No (2024 dio +71.481). | **Doc. 6178844931 del 07/12/2025:** debitó Escala Fija (−1.439.445) sin la Publicidad que la acompaña (2:1). **Faltan 719.723.** El resto (108.077) son diferencias de diciembre. |
| Hoffens | RT no (rigen AC 2024 por surtido); MY sí | En 2024 los "DIFERENCIAL 2024" (B2B y rebates) se cobraron el 31/03/2025. En el ranking (Casos semana 6) figura "No es igual en SAP que en el AC". | No encontré un error puntual. El 31/03/2026 hay 81,8 MM de aportes sin descripción (refs. 37597518/21/22–26, 37598007/08), probablemente los diferenciales 2025. Con eso, Pub + Fijo y B2B cerrarían. La escala pagada (170,8 MM) es el 8% de 2.135 MM, una base que no coincide con la web (Hoffens la calcula con sus números). Hace falta el texto de esas facturas (export de aportes manuales como el de NMC). |

---

## 1000044 – LEGRAND BTICINO CHILE SPA

1. **Identificación:** RUT 79602730-4, coincide con la web. El PDF RT 2024 dice "LTDA"; es el mismo RUT. Sección 51. Acuerdos aplicados:
   - **Retail:** acuerdo 2024, válido desde 01/01/2024. Es el último firmado.
   - **Mayorista:** acuerdo 2025, válido desde 01/01/2025.
2. **Condiciones:**
   - **Retail:** Publicidad 2,5%. Logística 2% (cláusula 15: solo si pasa por el CD). Escala Fija 5%. Escala Crecimiento con tramos en millones: base 2.423; más de 2.700 → 0,75%, 2.800 → 1,5%, 2.900 → 2%, 3.000 → 2,5%, 3.050 → 3%, 3.100 → 4%. Devoluciones "caso a caso", sin %; Mermas 0. B2B Sí.
   - **Mayorista:** Escala Fija 3%. Logística 2% (no hay compras al CD). B2B Sí.
3. **KSB1:** no está en el archivo, no se pudo cruzar.
4. **DEBIDO / PAGADO / DIFERENCIA:**

| Condición | DEBIDO | PAGADO | DIF |
|---|---:|---:|---:|
| Publicidad (RT 2,5%) | 51.826.385 | 51.365.140 | 461.245 |
| Escala Fija (RT 5% + MY 3%) | 103.886.843 | 103.520.289 | 366.554 |
| **Neteo Pub + Fijo** | 155.713.229 | 154.885.429 | **827.800** |
| Logística 2% (CD) | 40.449.593 | 40.449.594 | −1 |
| Escala Crecimiento | 0 | 1.044.736 | −1.044.736 |
| Otros B2B 0,15% | 3.121.287 | 3.114.257 | 7.030 |

5. **Conclusión:** CON RECLAMO por 827.800 (BORRADOR). Puntos a validar:
   - Toda la diferencia está en diciembre. Viene de las entregas de enero 2026 de OC 2025 (86,5 MM), que la web suma a diciembre. Hay que confirmar que no se debitaron en 2026 con el acuerdo 240750.
   - El Fijo 3% Mayorista Easy lo registró como "Publicidad" (acuerdo 234430). El neteo lo absorbe.
   - Escala Crecimiento: el pedido Retail 2025 es de 2.410 MM, menos que el primer tramo de 2.700 MM, así que no corresponde escala. Lo pagado (acuerdo 226474) es la escala 2024, liquidada en enero 2025.

## 1000071 – COM. IND. PLASTICOS HOFFENS S.A.

1. **Identificación:** RUT 96548020-K, coincide. Proveedor manual: no hay débitos tipo "Acuerdo" y todo se cobra con aportes manuales. Acuerdos aplicados:
   - **Retail CL5821/CL5101:** acuerdo 2024.
   - **Retail CL5840:** acuerdo 2024.
   - **Mayorista:** acuerdo 2025, válido desde 01/01/2025, pagado con NC PROVEEDOR.
2. **Condiciones:**
   - **RT CL5821/CL5101:** Publicidad 3%, Escala Fija 10%. Escala con base 1.600 MM; tramos más de 0 → 3%, 1.650 MM → 4%, 1.700 MM → 5%, 1.750 MM → 6%, 1.800 MM → 7%, 2.200 MM → 8%. B2B Sí.
   - **RT CL5840:** Publicidad 3%, Escala Fija 12%. Escala: más de 200 MM → 2%, 220 MM → 3%, 240 MM → 4%, 260 MM → 5%, 270 MM → 6%. B2B Sí. La Publicidad fija de 4 MM es contra evento y no se tomó.
   - **MY:** Escala Fija 5%, B2B Sí. Cláusula 15: no pasa por el CD.
3. **KSB1:** no está en el archivo. El PAGADO se reconstruyó con los aportes manuales (VI_Debitos + VIII), sin contar los conceptos rotulados 2024 (Escala 2024 de 253 MM y los "Diferencial 2024").
4. **Tabla:**

| Condición | DEBIDO | PAGADO | DIF |
|---|---:|---:|---:|
| Neteo Pub + Fijo (RT 13%/15% + MY 5%) | 284.300.386 | 353.501.558 | −69.201.172 |
| Escala Crecimiento (5821/5101 8% · 5840 6%) | 151.519.499 | 0 en 2025 | 151.519.499 |
| Otros B2B 0,15% | 4.528.324 | 0 | 4.528.324 |

5. **Conclusión:** CON RECLAMO por B2B, 4.528.324 (BORRADOR). Puntos a validar:
   - **CL5822** (575 MM de compras) no tiene acuerdo en la carpeta, pero Easy le cobra rebate. Si llevara el mismo 13% que CL5821, el neteo daría +5,6 MM.
   - **Escala Crecimiento:** los pedidos 2025 son 2.291 MM (CL5821/5101) y 334 MM (CL5840), así que los dos van al tramo máximo. En enero 2026 hay 170.806.471 de "Desc.Obt.p/Volumen" sin descripción. Si es la Escala 2025, la diferencia pasa a −19,3 MM y no hay reclamo de escala.

## 1000104 – LOUISIANA PACIFIC CHILE S.A.

- **Identificación:** RUT 96874160-8 según la web. El único acuerdo es "Acuerdo Comercial Easy Retail 2024 v1" (vigencia 01/01/2024–31/12/2024). Trae el RUT de Easy, no el de LP, así que no se puede controlar el RUT.
- **Condiciones:** rebate volumétrico en M3: escala anual de 1% sobre 21.000 m3 y 1,5% sobre 23.500 m3, más un 2% mensual por mix. Cláusula 5: 5% por camión OSB.
- **KSB1:** no está en el archivo.
- **PAGADO 2025:** todo con aportes manuales (Bonificación Fija 67.244.800 y Publicidad 22.569.134).
- **Conclusión:** PENDIENTE. Hacen falta los volúmenes en M3 por familia. El correo de Felipe Lagos confirma que LP paga sobre sus propios números, descontando fletes y rebates anteriores.

## 1000211 – SAINT-GOBAIN WEBER CHILE S.A

1. **Identificación:** RUT 80397900-6, coincide. Acuerdos aplicados:
   - **Mayorista:** válido desde 01/10/2024; la cláusula 15 dice "válido 2024 y 2025".
   - **Retail:** el último firmado es el de SOLCROM S.A. (mismo RUT), REMA 2021.
2. **Condiciones:**
   - **MY:** Escala Fija 4%. Logística 5,8% (solo CD). B2B Sí. Publicidad, Escala y Devoluciones N/A.
   - **RT (Solcrom):** Escala en millones: más de 260 → 2%, 270 → 3%, 280 → 3,5%, 290 → 4,5%. Publicidad no aplica.
3. **Faltantes KSB1** (para agregar en amarillo):

| Acuerdo | Condición | Documentos | Importe |
|---|---|---|---:|
| 234116 | Fijo MY | 6039701995 (11/05/25), 6088880272, 6091699374, 6138568379, 6152050065 | 809.728 |
| 234116 | Fijo MY, documentos de 2026 que van a dic-25 | 6206673616, 6228485660 y otros | 1.152.249 |
| 232993 | Escala Crecimiento | 6192172612 (26/12/25) | 449.160 |
| 235086 | Otros | varios documentos | 124.234 |

4. **Tabla:**

| Condición | DEBIDO | PAGADO | DIF |
|---|---:|---:|---:|
| Escala Fija MY 4% (Easy la debita como "Publicidad") | 41.686.838 | 46.489.245 | −4.802.407 |
| Escala Crecimiento RT 4,5% (pedido 321,7 MM > 290) | 14.864.543 | 18.421.981 | −3.557.438 |
| Logística 5,8% | 12.716.198 | 12.716.198 | 0 |
| Otros 0,15% | 2.058.741 | 2.298.623 | −239.882 |

5. **Conclusión:** SIN RECLAMO. Observaciones sobre el Excel de Ana:
   - En "Base Calculo" la Escala Retail está al 5%; el acuerdo Solcrom da 4,5%. Igual el resultado es negativo.
   - La Publicidad 3% Retail no tiene respaldo en ningún acuerdo, pero no está cargada en la Presentación.
   - No reclamar las ofertas OF-6028/6107/9465 (65,4 MM).

## 1000730 – NMC CHILE SPA

1. **Identificación:** RUT 89429100-1, coincide. Acuerdos aplicados:
   - **Retail 2025:** válido desde 01/01/2025.
   - **Mayorista 2025:** válido desde 01/01/2025.
2. **Condiciones:**
   - **RT:** Escala en millones: hasta 450 → 2%, 500 → 3%, 550 → 4%, 650 → 5%. Logística 4%. B2B Sí. Devoluciones caso a caso, sin %.
   - **MY:** Escala en miles: 247.000 → 1,5%, 283.000 → 2%, 322.000 → 3%, 366.000 → 3,5%, 400.000 → 4%. Logística por M3, sin %. **B2B No.**
3. **Faltantes KSB1:**

| Acuerdo | Condición | Documento | Fecha | Importe |
|---|---|---|---|---:|
| 232225 | Logística | 6118276311 | 11/09/2025 | 155.520 |
| 235055 | Otros | 6173505620 | 30/11/2025 | 30.000 |
| 235055 | Otros, documentos de 2026 que van a dic-25 | 6214881230 · 6232866970 | – | 4.315 |

4. **Tabla:**

| Condición | DEBIDO | PAGADO | DIF |
|---|---:|---:|---:|
| Escala Crecimiento RT 4% (vacíos 565 MM) + MY 4% (vacíos 454 MM) | 34.726.479 | 19.489.451 | **15.237.028** |
| Logística RT 4% (CD) | 20.179.221 | 20.179.222 | −1 |
| Otros 0,15% (solo RT) | 757.207 | 1.273.460 | −516.253 |

5. **Conclusión:** CON RECLAMO por 15.237.028, que es la **Escala Crecimiento Mayorista no pagada**.
   - Ana la tiene calculada en "Base Calculo" (14.534.298), pero no la pasó a la Presentación.
   - El PAGADO de escala incluye OF-9514-2 (15.197.335), que Ana tomó como escala. Hay que confirmar ese criterio.
   - **Corregido en la Presentación:** en la sección 57, la Escala Crecimiento DEBIDO (T43:T54) pasa a ser Retail + Mayorista, con la fórmula `'Base Calculo'!C22+'Base Calculo'!C23`, etc. El total pasa de 20.192.181 a 34.726.479.
   - **Corregido en Condiciones:** saqué el B2B 0,15% de las secciones 13 y 43, que son solo Mayorista (el Mayorista tiene B2B No).
   - En las secciones 49 y 57 sigue aplicándose el 0,15% también a las compras Mayoristas, unos 491.000 de más. Como Otros ya da negativo, no cambia la conclusión.
   - El total general de la Presentación da negativo por la columna Aportes Manuales (−28,6 MM: multas, más las cuotas de la escala 2022). Esa columna no se netea con la Escala Crecimiento.

## 1001339 – MADERAS ARAUCO S.A.

- **Identificación:** RUT 96510970-6. El acuerdo de la carpeta es "Acuerdo 2024 Easy firmado" (vigencia 01/01–31/12/2024). Proveedor manual.
- **Condiciones:** premios volumétricos por categoría (Maderas, Terciados, Mueblería), del 0,25% al 2,5% según el crecimiento en M3, más una bonificación de 0,5% en el tramo 5. Pago anual.
- **No hay Fijo, Publicidad ni Centralizada.**
- **KSB1:** no está en el archivo.
- **PAGADO 2025:** Bonificación Fija 666,6 MM, Publicidad 15,0 MM, Escala 690,0 MM (es la escala 2024, verificada en Hoja1 de Ana). En enero 2026 hay 1.162 MM de Desc.Obt.p/Volumen, probablemente la escala 2025.
- **Conclusión:** PENDIENTE. La **Centralizada 7%** cargada en Condiciones (DEBIDO 1.584 MM) **no aparece en el acuerdo de la carpeta**: hay que validar de dónde sale antes de reclamar los 204,7 MM. La escala volumétrica necesita los M3 2024/2025 por categoría.

## 1003494 – CINTAC S.A.I.C.

1. **Identificación:** RUT 76721910-5, coincide. Acuerdos aplicados:
   - **Mayorista 2025:** válido desde 01/01/2025.
   - **Retail 2025 general:** válido desde 01/02/2025, sin CL4321.
   - **Retail 2025 CL4321 Cubiertas:** válido desde 01/02/2025.
   - **Retail 2024:** rige solo enero 2025.
2. **Condiciones:**
   - **MY:** Fijo 3%. Escala en toneladas (base 1.555): 1.300 t → 1,75%, 1.450 t → 2,2%, 1.600 t → 2,6%, 1.750 t → 3,1%. **B2B No.**
   - **RT general:** Fijo y Publicidad 0. Cláusula 15: el 12% se pasó a precio desde el 20/01/2025, más un 2% de negociación extra mensual o trimestral. Escala en toneladas: 3.190 t → 1%, 3.350 t → 1,5%, 3.509 t → 2%. B2B Sí. Guía Experto 4 MM.
   - **RT CL4321:** Logística 2,22% (no hay compras al CD). B2B No.
   - **RT 2024 (enero):** Publicidad 3%, Fijo 7%, B2B Sí.
3. **KSB1:** no está en el archivo.
4. **Tabla:**

| Condición | DEBIDO | PAGADO | DIF |
|---|---:|---:|---:|
| Neteo Pub + Fijo (MY 3% + enero RT 10%) | 115.214.766 | 102.016.454 | 13.198.312 |
| Negociación extra 2% RT feb–dic (aportes manuales "Bonificación Fija") | 66.728.000 aprox. | 112.432.000 aprox. | −45.704.000 aprox. |
| **Neteo total del grupo** | 181.942.766 | 214.448.454 | **−32.505.688** |
| Otros B2B (RT ene + RT feb–dic sin CL4321) | 4.893.627 | 669.359 | **4.224.268** |

5. **Conclusión:** CON RECLAMO por B2B, 4.224.268. El B2B 2025 Retail no se debitó entre febrero y diciembre: solo hay débitos de B2B en enero. Puntos a validar:
   - Las escalas en toneladas no se pueden calcular sin los kilos.
   - Desc.Obt.p/Volumen: 2025 = 360,1 MM (incluye la escala 2024) y enero 2026 = 83,3 MM.
   - El Fijo 3% Mayorista Easy lo registra como "Publicidad" (acuerdo 234231).

## 4000006878 – KNAUF CHILE SPA

1. **Identificación:** RUT 76201342-8, coincide. Acuerdo Mayorista 2024, válido desde 01/01/2024; es el último firmado.
2. **Condiciones:** Fijo según la cláusula 15, con NC mensual sobre los rubros 4301/4302/4304/4305/4307: Placas 10%, Lanas 8%, resto 5%. Logística 2,5% (no hay compras al CD). **B2B No.**
3. **KSB1:** no hay faltantes; Ana ya los agregó.
4. **Tabla:**

| Condición | DEBIDO | PAGADO | DIF |
|---|---:|---:|---:|
| Fijo MY (Easy lo registra como "Publicidad") | **99.744.260** (antes 163.256.331) | 116.798.337 | −17.054.077 |
| Fijo RT (rebate Retail, sin acuerdo Retail) | 0 | 26.938.596 | −26.938.596 |

5. **Conclusión:** SIN RECLAMO.
   - **Error corregido:** en 'Base de Calculo'!B23 (enero) la fórmula era `=SUM(B18:B22)`, que suma las bases. Tenía que ser `SUMPRODUCT(B18:B22,$O$18:$O$22)`, como el resto de los meses. Enero pasa de 70.347.956 a 6.835.885.
   - Con el error, la Presentación daba CON RECLAMO por 14,36 MM.

## 4000008837 – PIMARES SPA

1. **Identificación:** RUT 77035479-K, coincide. Acuerdo Retail 2025, Pyme, válido desde 01/01/2025.
2. **Condiciones:** **Fijo 3,5%**. Escala en millones (base 1.070): más de 900 → 1%, 1.008 → 1,5%, 1.129 → 2%, 1.264 → 2,5%. Logística 1%. B2B Sí. Devoluciones caso a caso, sin %.
3. **KSB1:** el único faltante 2025 (231860 Logística, −293.168) Ana ya lo agregó. El de 2026 es del acuerdo 2026 (238902).
4. **Tabla:**

| Condición | DEBIDO | PAGADO | DIF |
|---|---:|---:|---:|
| Escala Fija 3,5% (+ Publicidad) | 29.746.718 | 10.022.123 | **19.724.595** |
| Escala Crecimiento 1% (pedido 934 MM > 900) | 8.499.062 | 0 | **8.499.062** |
| Logística 1% | 8.493.619 | 8.790.963 | −297.344 |
| Otros 0,15% | 1.274.859 | 1.275.559 | −700 |

5. **Conclusión:** CON RECLAMO por 28.223.657.
   - **Corregido en Condiciones:** Escala Fija 3,5% y Escala Crecimiento 1% en las secciones 41 y 47.
   - Ana tenía Fijo 2% en "Base Calculo", que es el acuerdo 2024, y no lo había cargado.
   - Punto a validar: el pedido supera el tramo de 900 MM por solo un 3,8%. No hay ZME80 para aplicar el criterio de descartar las líneas L y S.

## 4000008885 – WMART SPA

1. **Identificación:** RUT 77447267-3, coincide. Acuerdo REMA 2025, Pyme, válido desde 01/01/2025.
2. **Condiciones:** Logística 3%. B2B Sí; la captura SAP confirma Z033 0,15% y Z034 1 UF. Almacenamiento en CD 3%, que no se toma.
3. **KSB1:** no está en el archivo.
4. **Tabla:**

| Condición | DEBIDO | PAGADO | DIF |
|---|---:|---:|---:|
| Logística 3% | 17.486.897 | 17.486.897 | 0 |
| Otros B2B 0,15% | 874.607 | 0 | 874.607 |

5. **Conclusión:** CON RECLAMO por 874.607 de B2B. El 0,15% supera los 470.000, así que se mantiene el 0,15% y no se usa el piso UF. Lo cargado por Ana es correcto.

## 4000008973 – SOCIEDAD COMERCIAL TAPIA Y ALVAREZ

1. **Identificación:** RUT 76295412-5, coincide. Acuerdo REMA 2025, válido desde 01/01/2025.
2. **Condiciones:**
   - Fijo 2%.
   - Mermas 3%: va en Devoluciones, porque la Aclaración no trae %.
   - Logística 5,87%: la cláusula 15 dice que solo hay despacho directo a tienda, así que la base es 0.
   - B2B Sí.
3. **KSB1:** no está en el archivo.
4. **Tabla:**

| Condición | DEBIDO | PAGADO | DIF |
|---|---:|---:|---:|
| Escala Fija 2% | 13.950.572 | 16.281.986 | −2.331.414 |
| Devoluciones (Mermas 3%) | 20.925.858 | 24.231.374 | −3.305.516 |
| Otros 0,15% | 1.046.293 | 1.213.081 | −166.788 |

5. **Conclusión:** RESULTADO NEGATIVO, analizado sin reclamo. Lo cargado por Ana es correcto.

## Actualización – Pimares

Ana validó que la Escala Crecimiento **no llega al primer tramo**. La saqué de Condiciones y de la Presentación. Queda el reclamo por Escala Fija + Publicidad:

| | DEBIDO | PAGADO | DIF |
|---|---:|---:|---:|
| Escala Fija 3,5% + Publicidad | 29.746.718 | 10.022.123 | **19.724.595** |

## Actualización – Knauf (entregas 2026)

Criterio de Ana: todo lo que trae la descarga 2025, incluidas las entregas de 2026 de OC 2025, se toma en diciembre 2025 y se bonifica. En la "Base de Calculo", la columna M (diciembre) pasa a ser diciembre 2025 + entregas 2026 (fórmula `=dic+2026`). La nota de la fila 27 quedó actualizada.

| Mayorista | Entregas 2026 sumadas a diciembre | DEBIDO total |
|---|---:|---:|
| Placas 10% | 199.594.869 | 100.772.869 |
| Lanas 8% | 17.398.199 | 10.576.430 |
| Resto 5% | 9.356.175 | 10.214.112 |
| **Total** | | **121.563.411** |

- **Publicidad (rebate Mayorista):** DEBIDO 121.563.411 · PAGADO 116.798.337 · **+4.765.074**.
- **Escala Fija (rebate Retail, sin acuerdo Retail):** PAGADO 26.938.596.
- **Neteo del grupo Pub + Fijo:** −22.173.522 → **SIN RECLAMO**.
- **Punto a validar:** la NC "ACUERDOS FEBRERO 2026" (25/02/2026) se liquidó en 2026, así que no se cuenta.
