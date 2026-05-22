1.5
Agregamos:

-Los juegos van a poder ser fisicos o digitales, asi que junto con las categorias tiene que haber 2 checkboxes "Fisico" y "Digital" por default deben venir ambas chequeadas para que muestre la totalidad de juegos, pero tengo que poder filtrar entre los 2.

-Las metricas graficas de Metacritic y Generos, tienen que adaptarse a la plataforma que esta seleccionada y a su vez a si son juegos fisicos o digitales.
Es decir tengo que poder ver la metrica de los juegos fisicos de Playstation 3 por ejemplo.

-Te paso un excel de juegos todos digitales para agregar a la base con todas las estadisticas y lore de cada uno. Todos los que estan hasta ahora en la base son juegos fisicos, pero todos los de este excel son digitales.


1.4

📅 Filtro por Año
Dropdown con todos los años de la colección (1982–2025). Funciona para juegos, consolas y libros. El año se extrae dinámicamente del campo lore de cada ítem.
⭐ Metacritic (juegos)

Nuevo campo metacritic en todos los 218 juegos con puntajes reales/aproximados
Filtro por rango: 90+, 80+, 70+, 60+
El puntaje aparece en la card y en el modal, con color: 🟢 80+ / 🟡 60-79 / 🔴 <60
Gráfica de barras con distribución por rangos (90-100, 80-89, 70-79, 60-69, <60)

🎯 Filtro por Género

Nuevo campo genero en los 218 juegos, extraído y normalizado desde el lore (se unifican variantes como "Action RPG" / "Acción RPG", "Plataformas 2D" / "Plataformas", etc.)
Dropdown con todos los géneros únicos
Gráfica de barras ordenada de más a menos frecuente
El género aparece en cada card con un tag en color violeta

Los tres filtros nuevos se combinan entre sí y con los ya existentes (búsqueda, tipo, plataforma).
