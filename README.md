# Telugu Wikipedia positional index data

This repository contains the exact 100-document sample used for the assignment
results and the index built from it. The sample contains 11,588 token positions
and 5,270 distinct terms.

- `data/telugu_wiki.jsonl` is the exact input corpus.
- `data/SOURCES.tsv` lists the Telugu Wikipedia articles and their history links.
- `output/index/` contains the built vocabulary, postings, document metadata,
  and build statistics.

To reproduce the submitted results, copy `data/telugu_wiki.jsonl` into `data/`
inside the extracted source project and run `python run.py` from the project folder.

The article text is by Telugu Wikipedia contributors. See the article links in
`data/SOURCES.tsv` for attribution. Wikipedia text is available under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), subject to
applicable [Wikimedia terms](https://foundation.wikimedia.org/wiki/Policy:Terms_of_Use)
and article notices.
