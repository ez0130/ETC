# FDE Screen
## Package Sorter

This codes implements a Python function for sorting packages into the correct stack based on their volume and mass.

### Objective

Automatically dispatch packages using the following classification:

- Bulky: Volume ≥ 1,000,000 cm³ OR any dimension (width, height, length) ≥ 150 cm  
- Heavy: Mass ≥ 20 kg

### Stacks

| Category   | Description                                      |
|------------|--------------------------------------------------|
| `STANDARD` | Not bulky and not heavy                          |
| `SPECIAL`  | Either bulky or heavy (but not both)             |
| `REJECTED` | Both bulky and heavy                             |

---

