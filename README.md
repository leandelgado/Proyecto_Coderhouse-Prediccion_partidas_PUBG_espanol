# Proyecto_Coderhouse-Prediccion_partidas_PUBG_espanol
Proyecto Coderhouse curso Data Science

3 entregas correspondientes al curso de Data Science de Coderhouse. El objetivo final es poder predecir el ranking de un jugador basado en sus estadísticas de partida.

## *Primera entrega*

La primera entrega se basó en un archivo obtenido de kaggle, el cual consistía en un compilado de resultados de métricas de partidas como daño infligido, asistencias, 
muertes, etc. y su correspondiente resultado, para jugadores de variado nivel. Se realizó una imputación de nulos, EDA estudiando algunas de las variables y obtención
de insights; y por último una aplicación de un árbol de decisión para nuestro caso de regresión con sus correspondientes métricas.

## *Segunda entrega*

Para la segunda entrega, se realizó la comunicación con la API del juego, descargando información de las partidas correspondientes a un listado de jugadores. La 
información se fue guardando en un df. Se limpió el mismo y se transformaron los datos en el tipo correspondiente. Luego se realizó un profiling y se buscaron 
respuestas a preguntas puntuales mediante visualizaciones; obteniengo insights a través de ellas.

## *Entrega final*

Para la última entrega, a partir de la información descargada mediante la API, se reforzó la obtención de insights, se crearon luego variables sintéticas y se
determinaron las variables más significativas mediante un forward selection. A partir de estas variables, se aplicaron varios modelos de regresión con sus
parametros por defecto y se seleccionaron los 5 mejores. Para estos 5, se realizo un hypertuneo con validación cruzada. Se seleccionó el que obtuvo mejor
rendimiento.
