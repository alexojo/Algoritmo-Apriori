# Algoritmo-Apriori
- **Universidad Nacional de San Antonio Abad del Cusco**
- **Escuela Profesional de Ingenieria Informatica y de Sistemas**

## Description 

Este repositorio, tiene implementado el algoritmo Apriori en un archivo .ipynb. Se desarrollo las siguientes funciones

- 📝 `get_frequent_itemsets(playlists, min_support)`: Recibe la esctructura de datos que contiene a las playlists y retorna una estructura con los itemsets frecuentes, bajo un umbral mínimo de confianza.
- 📝 `generate_association_rules(frequent_itemsets, confidence = 0, lift =0)`: Recibe los itemsets frecuentes generados por la función anterior y retorna las reglas de asociación. Se le puede entregar umbrales de confianza o lift para las reglas que se retornarán. Por ejemplo, si se llama esta función con los ar- gumentos confidence = 0.5 y lift = 1.2, se espera que se retornen aquellas reglas que cumplan con una confianza ≥ 0.5 y un lift ≥ 1.2.

La base de datos a utilizar corresponde a múltiples playlists de la plataforma spotify creadas por usuarios de esta.
- 📝 `spotify.npy`


## Authors ✒️
* **Alexander Junior Monzon Montalvo** - [alexojo](https://github.com/alexojo)
---
