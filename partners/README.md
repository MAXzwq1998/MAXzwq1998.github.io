# Partner logos

Official institution logos used on the Home page social proof marquee.

## Source JPEGs (inputs)

| File | Institution |
|------|-------------|
| `university-of-cambridge.jpg` | University of Cambridge |
| `yale-university.jpg` | Yale University |
| `university-of-hong-kong.jpg` | The University of Hong Kong |
| `abbvie.jpg` | AbbVie |
| `sanofi.jpg` | Sanofi |
| `astrazeneca.jpg` | AstraZeneca |

## Marquee assets (used on site)

Monochrome transparent PNGs (`*-mono.png`) are generated from the JPEGs via:

```bash
python3 scripts/prepare-partner-logos.py
```

Paths are configured in `config/home.ts` under `homeSocialProofContent.partners`.
