# Sentinel_PyGEE
Extrair dados do Sentinel-2 através do Google Earth Engine + Python!

# Sentinel-2 Downloader com NDVI, RGB e Falsa Cor

Este script permite ao usuário:
- Selecionar uma área de interesse via shapefile.
- Aplicar buffer em metros.
- Selecionar imagens Sentinel-2 em um intervalo de datas.
- Visualizar a imagem no mapa interativo.
- Exportar as imagens nos formatos: RGB, Falsa Cor e NDVI.

## Requisitos

- Python >= 3.8
- Google Earth Engine (GEE) ativado na conta
- Pacotes Python: `geemap`, `geopandas`, `shapely`, `ipywidgets`
