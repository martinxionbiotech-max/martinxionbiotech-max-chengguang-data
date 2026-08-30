<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    {
      "@type": "ListItem",
      "position": 1,
      "name": "Home",
      "item": "https://data.chengguangenergy.com/"
    },
    {
      "@type": "ListItem",
      "position": 2,
      "name": "Cross Reference",
      "item": "https://data.chengguangenergy.com/cross-reference/"
    }
  ]
}
</script>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Are cross-reference equivalents identical?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. Equivalents are based primarily on physical case dimensions. Electrical specifications such as CCA and Ah may differ, so always verify the data sheet."
      }
    },
    {
      "@type": "Question",
      "name": "What is the DIN equivalent of the 65D26?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The 65D26 cross-references to DIN66 (56638) and BCI Group 48 (H6) as a same-case-family comparison."
      }
    },
    {
      "@type": "Question",
      "name": "What is the DIN equivalent of the 105D31?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The 105D31 cross-references to DIN80 (58043) and BCI Group 27, but terminal layout should be verified."
      }
    },
    {
      "@type": "Question",
      "name": "Why should I verify terminals when cross-referencing?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Terminal type and polarity layout can differ between standards even when the case size is similar."
      }
    }
  ]
}
</script>

# Battery Cross Reference

Find equivalent and related battery models across JIS, DIN, and BCI standards.

!!! warning "Equivalents Are Not Identical"
    Different standards use different test methods. A JIS battery and its DIN "equivalent" may have different CCA ratings even when physically interchangeable. Always verify specifications.

---

## Cross Reference Tables

| From | To | Reference |
|------|----|-----------|
| JIS | DIN | [JIS to DIN Cross Reference](jis-to-din.md) |
| DIN | BCI | [DIN to BCI Cross Reference](din-to-bci.md) |
| Model | Equivalent | [Model Equivalents](model-equivalents.md) |

---

## Common Cross-References

| JIS Model | DIN Equivalent | BCI Group | Notes |
|-----------|---------------|-----------|-------|
| 55B24 | — | Group 35/51R | Similar case size, verify CCA |
| 65D26 | 56638 (DIN66) | Group 48 (H6) | Same case family, different specs |
| 105D31 | 58043 (DIN80) | Group 27 | Verify terminal layout |
| 145G51 | 60038 (DIN100) | Group 31 | Heavy duty applications |
| 95E41 | — | Group 49 (H8) | Longer case than DIN100 |

!!! note
    These cross-references are based on physical case dimensions. Electrical specifications (CCA, Ah) may differ. Always consult the product technical data sheet.
