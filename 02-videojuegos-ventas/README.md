# Ventas de videojuegos: ¿dónde invertir?

## Pregunta de negocio
¿Que genero vende mas?
<img width="887" height="507" alt="imagen" src="https://github.com/user-attachments/assets/f83a9615-069d-461a-8c79-d9680b227fe8" />


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
¿Que genero vende mas?

## Recomendación
(Al final.)

## Limitaciones
(Al final.)

## Cómo reproducirlo
Librerías: pandas, seaborn, matplotlib. Ejecutar `analisis.ipynb` de arriba
abajo con `vgsales.csv` en la misma carpeta.
