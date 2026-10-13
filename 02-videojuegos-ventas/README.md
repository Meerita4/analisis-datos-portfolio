# Ventas de videojuegos: ¿dónde invertir?

## Pregunta de negocio
[Una o dos frases. Por ejemplo: qué decisión quiere tomar una editora
sobre géneros y plataformas. Escríbela con tus palabras.]

## Datos
- **Fuente:** dataset "Video Game Sales" de Kaggle (autor: GregorySmith).
- **Tamaño:** 16.598 juegos y 10 columnas (nombre, plataforma, año, género,
  editora y ventas por región en millones de unidades).
- **Limitación:** son datos históricos, que llegan aproximadamente hasta 2016.
  No reflejan el mercado actual.

## Limpieza
| Problema | Cantidad | Qué hice | Por qué |
|---|---|---|---|
| Nulos en `Year` | 271 | [tu decisión] | [tu motivo] |
| Nulos en `Publisher` | 58 | [tu decisión] | [tu motivo] |
| `Year` como decimal | todas | [tu decisión] | [tu motivo] |

Resultado: [cuántas filas quedaron y qué porcentaje perdiste].

## Hallazgos
(Se rellena según avances.)

## Recomendación
(Al final.)

## Limitaciones
(Al final.)

## Cómo reproducirlo
Librerías: pandas, seaborn, matplotlib. Ejecutar `analisis.ipynb` de arriba
abajo con `vgsales.csv` en la misma carpeta.
