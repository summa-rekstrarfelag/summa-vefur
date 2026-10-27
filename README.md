# summa.is

Heimasíða Summu rekstrarfélags hf. Kyrrstæð HTML-síða hýst með GitHub Pages.

## Uppbygging

| Slóð | Efni |
|---|---|
| `index.html` | Forsíða (íslenska) |
| `um-summu/`, `radgjof/`, `sjodir/`, `skilmalar/` | Íslenskar síður |
| `en/`, `en/about/`, `en/services/`, `en/investment-funds/`, `en/licenses/` | Enskar síður |
| `upplysingar/`, `en/heim-english/` | Framvísanir frá gömlum slóðum |
| `wp-content/uploads/…` | Stefnuskjöl (PDF), á sömu slóðum og á gamla WordPress-vefnum svo eldri tenglar virki |
| `assets/` | Útlit (CSS), letur, myndir |

## Breytingar

- Allur texti er beint í HTML-skránum. Lítil textabreyting: opna skrána á github.com → blýantur (Edit) → *Commit changes*. Síðan uppfærist sjálfkrafa eftir 1–2 mínútur.
- Íslensk og ensk útgáfa eru aðskildar skrár. Muna að breyta báðum.
- Starfsmannamyndir: `assets/img/starfsfolk/`, 600×800 px, svarthvítar.

## Letur

Jost (SIL Open Font License 1.1, sjá `assets/fonts/OFL-Jost.txt`). Futura er ekki notuð þar sem ekkert vefleyfi liggur fyrir.

## Áður en síðan fer á summa.is

- [ ] Fjarlægja `noindex`, forskoðunarborða og `robots.txt`-bann (stillt í smíðaskriftunni sem `PREVIEW`).
- [x] PDF-skjöl í `wp-content/uploads/` (sömu skrár og á gamla vefnum, júní 2024).
- [ ] Mynd af Ólöfu, ferilstexti Önnu, yfirlestur á enskri þýðingu um Ægi, forsíðutexti.
- [ ] Bæta við `CNAME` (summa.is) og breyta DNS.
