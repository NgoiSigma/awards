# Public roles

Store profiles as `<person-id>.yaml` under `recipients/`, `curators/`, or `verifiers/`. One person may have multiple role profiles with the same stable ID and display name. These directories start empty.

Profiles contain a public display name, professional affiliation, role, public professional links, consent attestation and curator recusals. Recipient profiles include a `publication_consent` attestation reference. Each recusal links an entry ID, date, a brief public explanation, and an optional public discussion URL. Do not include private contact, payment, or identity details. Record no recusals as an explicit empty list.

See the [person template](../docs/templates/person.yaml.example) and [schema](../data/schema/person.schema.json).
