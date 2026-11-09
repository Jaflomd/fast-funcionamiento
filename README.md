# FAST · Evaluación del funcionamiento

Aplicación web, de acceso abierto, para aplicar y registrar la **Functioning Assessment Short Test (FAST)** en rehabilitación psiquiátrica.

**Usar en línea:** https://jaflomd.github.io/fast-funcionamiento/

## Qué hace

- **Entrevista:** un ítem por pantalla, con qué evalúa, preguntas sugeridas, ejemplos para cada puntaje (0–3) y precauciones.
- **Registro rápido:** los 24 ítems en una tabla, para transcribir una entrevista ya hecha.
- **Resultado:** total (0–72), subtotales por dominio, bandas referenciales y alertas (dominio cognitivo, limitación física, ítems no evaluables, desempleo por causa externa).
- **Salidas:** resumen para la historia clínica, hoja imprimible A4 con firma y CSV.
- **Seguimiento:** historial local y cambio frente a la evaluación previa del mismo ID.

## Dominios

| Dominio | Ítems | Rango |
|---|---|---|
| Autonomía | 1–4 | 0–12 |
| Funcionamiento laboral | 5–9 | 0–15 |
| Funcionamiento cognitivo | 10–14 | 0–15 |
| Finanzas | 15–16 | 0–6 |
| Relaciones interpersonales | 17–22 | 0–18 |
| Ocio | 23–24 | 0–6 |
| **Total** | 1–24 | 0–72 |

## Privacidad

Es un solo archivo HTML. No envía datos a ningún servidor. Las respuestas se guardan solo en el navegador de quien la usa (`localStorage`). Use iniciales o un código, nunca el nombre completo del paciente.

También funciona sin internet: descargue `index.html` y ábralo en el navegador.

## Advertencias

- Las preguntas auxiliares y los ejemplos de puntuación son una guía operativa para mejorar la concordancia entre evaluadores. **No reemplazan la redacción oficial de la FAST** ni son anclajes validados por sus autores.
- Las bandas de interpretación (0–11 sin deterioro, 12–20 leve, 21–40 moderado, >40 grave) provienen de trastorno bipolar y son referenciales.
- Es una herramienta de apoyo. No sustituye el juicio clínico ni una evaluación neuropsicológica.

## Referencias

- Rosa AR, Sánchez-Moreno J, Martínez-Aran A, et al. Validity and reliability of the Functioning Assessment Short Test (FAST) in bipolar disorder. *Clin Pract Epidemiol Ment Health*. 2007;3:5.
- Bonnín CM, Martínez-Arán A, Reinares M, et al. Thresholds for severity, remission and recovery using the Functioning Assessment Short Test (FAST) in bipolar disorder. *J Affect Disord*. 2018;240:57–62.

La escala FAST pertenece a sus autores. Este proyecto no está afiliado a ellos.

## Autor

MEd MC Javier A. Flores Cohaila · ORCID [0000-0002-9169-2094](https://orcid.org/0000-0002-9169-2094)

## Licencia

Código bajo licencia MIT (ver `LICENSE`).
