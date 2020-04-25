---
title: "cep-to-coords: Pacote Python para converter CEP em coordenadas geográficas (latitude e longitude)"
date: 2019-12-16
tags: [data-science, package, python]
header:
  image: "/assets/images/cep_to_coords/cep_to_coords.png"
---

Pacote Python para transformar CEP em latitude e longitude

[https://github.com/millengustavo/cep-to-coords](https://github.com/millengustavo/cep-to-coords)

# Como usar:
1. Instale:

```bash
git clone https://github.com/millengustavo/cep-to-coords.git
cd cep-to-coords
git checkout master
pip install -e .
```

2. Converta um CEP para latitude e longitude:

```python
from cep_to_coords.geocode import cep_to_coords

lat, lon = cep_to_coords('22070-900')

print(f'Latitude: {lat}, Longitude: {lon}')
Latitude: -22.9864082, Longitude: -43.189592
```

# Testando

```bash
python -m unittest discover
```

# Documentação

[https://cep-to-coords.readthedocs.io/en/latest/](https://cep-to-coords.readthedocs.io/en/latest/)
