# 🌿 Low-Cost Ecology — Recursos Abiertos

> Lista curada de bases de datos, softwares e imágenes gratuitos o de bajo costo para investigación ecológica. Recurso complementario al paper **"Ecología en tiempos de recortes"**.

🌐 **Sitio web:** `https://agostinatorresm.github.io/low-cost-ecology`

---

## ¿Cómo sugerir un recurso?

1. Abrí un [nuevo Issue](../../issues/new?template=sugerencia.md&labels=sugerencia) con el template
2. El equipo lo revisará antes de publicarlo
3. Si es aprobado, lo agregamos al `resources.json` y se publica automáticamente

## Estructura del proyecto

```
low-cost-ecology/
├── index.html        # Sitio web principal
├── resources.json    # Lista de recursos (editá este archivo)
└── README.md
```

## Agregar un recurso aprobado

Editá `resources.json` y agregá un objeto con este formato:

```json
{
  "id": 11,
  "name": "Nombre del recurso",
  "category": "Database | Software | Images | Other",
  "description": "Descripción breve y útil.",
  "url": "https://...",
  "tags": ["tag1", "tag2"],
  "free": true,
  "added": "2024-01"
}
```

## Licencia

CC BY 4.0 — Libre para usar y compartir con atribución.
