### Brazilian Schools Map - Infrastructure Analysis ###

Steps to create map: 
  1. Filter and clean database from [Brazilian School Census](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/censo-escolar) 2023
  2. Merge data with [schools catalogue](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/inep-data/catalogo-de-escolas) that contains schools coordenates
  3. Transform into geojson file
  4. Plot dots with geopandas
  5. Add [Brazil border](https://www.ibge.gov.br/geociencias/organizacao-do-territorio/malhas-territoriais/15774-malhas.html) and [indigenous lands](https://www.gov.br/funai/pt-br/atuacao/terras-indigenas/geoprocessamento-e-mapas) for context
  6. Create maps

  7. With Folium package, export to html file


