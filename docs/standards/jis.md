# JIS Battery Standard

**JIS** (Japanese Industrial Standard) is the dominant automotive battery specification across Asia, Africa, the Middle East, and Oceania.

## How JIS Battery Codes Work

JIS battery model numbers encode physical dimensions and performance class:

```
Example: 65D26

65 = Performance class (higher = more capacity/CCA)
D  = Width/depth class (D = wide, B = narrow)
26 = Length in cm (26 cm)
```

### Common JIS Formats

| Format | Example | Meaning |
|--------|---------|---------|
| `NN L NN` | 65D26 | Performance + Width class + Length |
| `NNN L NN` | 105D31 | 3-digit performance for larger batteries |
| `NNN L NN` | 145G51 | G-class for heavy-duty batteries |

### JIS Terminal System

JIS batteries use the **T1** terminal type with two sizes:

| Terminal | Post Diameter | Used On |
|----------|:---:|---------|
| T1 (small) | ~14.7 mm (+) / ~13.0 mm (-) | Standard SLI batteries |
| T1 (large) | ~19.5 mm (+) / ~17.9 mm (-) | Heavy-duty batteries |

### JIS Hold-Down System

JIS batteries use **B00** (top frame) hold-down — a metal frame that clamps across the top of the battery.

### JIS Polarity Convention

JIS standard polarity is **[0]** (right-positive):
- Left terminal: Negative (-)
- Right terminal: Positive (+)

When viewed from the terminal side with terminals closest to you.

---

## Chengguang JIS Battery Models

| Model | Type | Capacity | CCA |
|-------|------|----------|-----|
| [55B24](../battery-models/jis/55b24.md) | SLI | 45 Ah | 370 A |
| [55D23](../battery-models/jis/55d23.md) | SLI | 60 Ah | 500 A |
| [65D26](../battery-models/jis/65d26.md) | SLI | 55–70 Ah | 450–580 A |
| [95E41](../battery-models/jis/95e41.md) | SLI | 100 Ah | 750 A |
| [105D31](../battery-models/jis/105d31.md) | SLI | 90 Ah | 650 A |
| [145G51](../battery-models/jis/145g51.md) | Heavy Duty | 120–135 Ah | 800–900 A |
| [190H52](../battery-models/jis/190h52.md) | Heavy Duty | 200 Ah | 1,100 A |
