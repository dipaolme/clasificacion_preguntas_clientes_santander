# Clasificacion_preguntas_clientes_santander

Santander nos propone un desafío basado en NLP, donde lo que se busca es entender las preguntas que hacen los clientes con el fin de ser más asertivos en las respuestas, 
esto es fundamental para brindar una mejor experiencia al usuario.

Link:
https://metadata.fundacionsadosky.org.ar/competition/21/


El training set cuenta  con 20104 preguntas, 
clasificadas en 352 etiquetas/intenciones con marcado desbalance entre las mismas.
 
Se utilizo la matriz de embeddings GloVe de  300 dimensiones (https://github.com/dccuchile/spanish-word-embeddings)

Se probaron dos modelos con arquitecturas diferentes, una RNN y otra CNN.

Todo:

	- over sampling
	- ensamble con modelo base  
