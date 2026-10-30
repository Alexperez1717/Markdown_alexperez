# 🔴⚪ Club Atlético de Madrid

Bienvenido al repositorio de documentación sobre el **Club Atlético de Madrid**. Este proyecto sirve como práctica para demostrar el uso de *Markdown* en GitHub, combinando estilos de texto, tablas, bloques de código y elementos multimedia.

> "Nunca dejes de creer." — **Diego Pablo Simeone**

---

## Historia y Filosofía

El **Atlético de Madrid** fue fundado el *26 de abril de 1903* por un grupo de estudiantes vascos afincados en Madrid. Conocidos popularmente como los ***colchoneros*** debido a las rayas rojas y blancas de las antiguas fundas de colchones, el club se caracteriza por su espíritu de lucha, sacrificio y resiliencia.

Antiguamente jugaban en el mítico Estadio Vicente Calderón, pero desde el año 2017 disputan sus partidos como locales en el moderno **Riyadh Air Metropolitano**.

---

## Palmarés y Estadísticas

### Títulos principales 

* **Competiciones Nacionales**
  * 11 Ligas de Primera División
  * 10 Copas del Rey
  * 2 Supercopas de España
* **Competiciones Europeas e Internacionales**
  * 3 UEFA Europa League
  * 3 Supercopas de Europa
  * 1 Recopa de Europa
  * 1 Copa Intercontinental

### Leyendas con más partidos 

1. **Koke Resurrección** (749 partidos)
2. **Adelardo Rodríguez** (553 partidos)
3. **Jan Oblak** (551 partidos)
4. **Tomás Reñones** (483 partidos)

---

## Evolución de los Estadios 

A continuación se muestra una comparativa de los principales estadios históricos del club:

| Estadio | Inauguración | Capacidad Aprox. | Ubicación |
| :--- | :---: | :---: | ---: |
| Metropolitano de Madrid | 1923 | 35.800 | Reina Victoria |
| Vicente Calderón | 1966 | 54.907 | Paseo de los Melancólicos |
| Riyadh Air Metropolitano | 2017 | 70.460 | San Blas-Canillejas |

---

## Gestión de Datos del Club 

Podemos consultar los datos de la plantilla usando un comando rápido en consola como `curl -s https://api.atleticodemadrid.com/plantilla` o mediante scripts estructurados.

### Ejemplo de consulta en SQL:
```sql
SELECT nombre, dorsal, posicion 
FROM jugadores_atleti 
WHERE titular = 'SÍ' 
ORDER BY dorsal ASC;
```

### Ejemplo de ficha en JSON:
```json
{
  "club": "Atlético de Madrid",
  "fundacion": 1903,
  "entrenador": "Diego Pablo Simeone",
  "colores": ["Rojo", "Blanco", "Azul"]
}
```

---

## Enlaces e Imágenes

* Puedes visitar la [Web Oficial del Atlético de Madrid](https://www.atleticodemadrid.com/) para consultar noticias y entradas.
* Consulta el perfil oficial de LaLiga en [LaLiga - Atlético de Madrid](https://www.laliga.com/clubes/atletico-de-madrid).
* Documento con [información extra.](docs/detalles.md)

### Escudo del club: 
![Escudo del Atlético de Madrid](assets/escudo.png)

---

## Mi instituto
![Mi instituto IES Clara del Rey](https://thumb.wikimedia.org/wikipedia/commons/thumb/2/28/I.e.s._clara_del_rey_%28Prosperidad%2C_Madrid%29.jpg/960px-I.e.s._clara_del_rey_%28Prosperidad%2C_Madrid%29.jpg?utm_source=commons.wikimedia.org&utm_campaign=imageinfo&utm_content=thumbnail)
