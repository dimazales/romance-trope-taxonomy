# Romance trope taxonomy (multilingual)

A reader-facing taxonomy of **118 romance tropes** — enemies to lovers, fake dating,
grumpy/sunshine, fated mates, forced proximity, second chance, and more — with labels, the search
terms readers actually use, and short genre definitions in **English, German, French, Spanish,
Italian, Brazilian Portuguese and Dutch**. Curated by [Mozaika Publications](https://mozaikallc.com/)
from its multilingual romance catalog.

Categories: subgenre (38), relationship-dynamic (30), character-archetype (11), plot-device (31), setting (5), tone-heat (3).

## Files

- `tropes.jsonl` — one JSON object per trope (full detail)
- `tropes.csv` — flat table: slug, category, label and definition per language, work count, URL

## Fields (tropes.jsonl)

| Field | Meaning |
| --- | --- |
| `slug` | Canonical trope id (kebab-case) |
| `category` | relationship-dynamic · character-archetype · setting · plot-device · subgenre · tone-heat |
| `labels` | Language → the label readers use (German readers often use the English term) |
| `aliases` | Language → other search terms for the same trope |
| `definitions` | Language → 1–2 sentence genre definition (general, not about a specific book) |
| `member_slugs` | Finer-grained catalog tags merged into this trope |
| `work_count` | Mozaika books tagged with this trope |
| `example_works` | Example Mozaika titles with catalog links |
| `related_tropes` | Tropes that most often appear together with this one |
| `catalog_url` | The trope's page in the catalog |

## Uses

Trope tagging and genre classification, cross-lingual alignment of reader vocabulary, and
book recommendation / retrieval research. Browse the books and "books like …" guides at
https://books.mozaikallc.com/

## About and updates

Maintained by Mozaika Publications alongside the catalog at https://books.mozaikallc.com/. Its
purpose is to help readers, and the AI assistants they ask, find books close to ones they already
love. It is regenerated with every catalog update and republished at this same address, so new
languages and new "books like …" guides keep arriving.

## License and citation

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please credit **Mozaika Publications**
and link https://books.mozaikallc.com/

```bibtex
@dataset{mozaika_romance_trope_taxonomy_2026,
  title  = {Romance trope taxonomy (multilingual)},
  author = {{Mozaika Publications}},
  year   = {2026},
  url    = {https://books.mozaikallc.com/}
}
```

## Also on

- GitHub: https://github.com/dimazales/romance-trope-taxonomy
