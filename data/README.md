# Machine-readable data

[awards.json](awards.json) and [candidates.json](candidates.json) are generated from source records. Both use `{ "schema_version": 1, "items": [] }` when no structured records exist. The [candidate register](../candidates/README.md#candidate-register) is the public notice table and is not included in this generated index; an empty candidate index does not mean no candidates are in public review. Each item includes the source entry, repository-relative path, English Markdown, verification record and active statement. Records are sorted by stable entry ID. Candidate data does not represent an award.

Run `python scripts/manage.py build` after source changes and commit both outputs in the same PR. Do not edit the generated JSON directly. `python scripts/manage.py check` detects drift. Schema IDs use the reserved `example.invalid` domain as local identifiers and are resolved from [schema/](schema/); they are not remote schema services.

See [record maintenance](../docs/records.md) for fields and validation boundaries. A future website should render these files and `docs/`; no website or Pages deployment is included in this initialization.
