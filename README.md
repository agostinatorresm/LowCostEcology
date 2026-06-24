# 🌿 LowCostEcology — Open Resources

> A curated list of free or low-cost databases, software, and images for ecological research. Companion resource to the paper **"Ecology on a tight budget"**.

🌐 **Website:** `https://agostinatorresm.github.io/LowCostEcology`

---

## How to suggest a resource

1. Open a [new Issue](../../issues/new?labels=suggestion) using the suggestion template
2. The team will review it before publishing
3. If approved, we add it to `resources.json` and it goes live automatically

## Project structure

```
LowCostEcology/
├── index.html        # Main website
├── resources.json    # Resource list (edit this file to add new ones)
└── README.md
```

## Adding an approved resource

Edit `resources.json` and add an object with this format:

```json
{
  "id": 27,
  "name": "Resource name",
  "category": "Database | Dataset | Software | Images",
  "description": "Brief and useful description.",
  "url": "https://...",
  "tags": ["tag1", "tag2"],
  "free": true,
  "added": "2024-01"
}
```

## License

CC BY 4.0 — Free to use and share with attribution.
