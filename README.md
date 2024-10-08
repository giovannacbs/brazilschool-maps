### Brazilian Schools Map - Infrastructure Analysis ###

Website with maps for Internet and Potable Water: https://brazilschools2023.netlify.app/

Steps to create maps: 
  1. Filter and clean database from [Brazilian School Census](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/censo-escolar) 2023
  2. Merge data with [schools catalogue](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/inep-data/catalogo-de-escolas) that contains schools coordenates
  3. Transform into geojson file
  4. Plot dots with geopandas
  5. Add [Brazil border](https://www.ibge.gov.br/geociencias/organizacao-do-territorio/malhas-territoriais/15774-malhas.html) and [indigenous lands](https://www.gov.br/funai/pt-br/atuacao/terras-indigenas/geoprocessamento-e-mapas) for context
  7. With Folium package, export to html file

![Map1](https://github.com/giovannacbs/brazilschool-maps/blob/main/potablewater2023.png?raw=true)
![Map2](https://github.com/giovannacbs/brazilschool-maps/blob/main/internet_map.png?raw=true)
