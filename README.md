# Rootherhub Papers: Public Registry

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22823361.svg)](https://doi.org/10.5281/zenodo.22823361)

Editorial papers by **Jair Ibarra** (Rootherhub) on architecture, hospitality, operations, and human judgment after image-making became automated.

## How this registry works

Every completed paper is registered here with its title, abstract, authorship, completion date, and the **SHA-256 fingerprint** of the exact approved manuscript file. The fingerprint plus the git commit timestamp is verifiable proof that the complete text existed in that form on the registered date.

As of September 17, 2026 the author self-publishes here. A published paper's entry carries its full text, and the byte-exact approved master sits in `manuscripts/` so the fingerprint can be reproduced. Papers registered but not yet published remain privately held. Revisions to a published paper are registered as a new version with a new fingerprint; the prior fingerprint stays in the paper's amendment record and in git history.

**Verification:** `sha256sum manuscripts/<paper>.master.md` must reproduce the fingerprint recorded in that paper's entry at the commit in which it was registered. The fingerprint of a published paper never changes; a revision would be registered as a new version with its own fingerprint and the prior one kept in git history.

## Papers

| # | Title | Status | Registered | Published here |
|---|---|---|---|---|
| 001 | [I Learned Architecture Before Machines Learned to Imagine It](papers/001-learned-architecture-before-machines.md) | Public · full text | 2026-07-28 | 2026-09-17 |
| 002 | [When Everyone Can Design a Hotel, Judgment Becomes the Luxury](papers/002-when-everyone-can-design-a-hotel.md) | Public · full text | 2026-07-28 | 2026-09-17 |
| 003 | [The Author Was Never in the Folder](papers/003-the-author-was-never-in-the-folder.md) | Public · full text | 2026-08-08 | 2026-09-17 |
| 004 | Boutique Hospitality After Infinite Aesthetics | In progress | not yet | not yet |

## Authorship

Jair Ibarra is the author of every paper here: the argument, the experience it draws on, the judgment, and the final voice are his. AI tools are used as editorial instruments in the process. See [AUTHORSHIP.md](AUTHORSHIP.md) for the disclosure in full.

## Archive and citation

Every release of this registry is archived on Zenodo with a DOI. First archived release, 2026-09-17: [10.5281/zenodo.22823361](https://doi.org/10.5281/zenodo.22823361). The three published papers are included as PDFs in `pdf/`, each carrying its fingerprint, license and canonical URL. Citation metadata is in `CITATION.cff` and `.zenodo.json`.

## Author

Jair Ibarra is a Mexican architect and founder of Rootherhub, an AI architecture and hospitality intelligence practice. ORCID [0009-0008-8796-8888](https://orcid.org/0009-0008-8796-8888).

Inquiries: jair@rootherhub.com · rootherhub.com

## License

Published papers are released under [CC BY-ND 4.0](LICENSE.md): share and redistribute with attribution and a link to the canonical record; no modified versions, partial reproductions presented as the whole, or translations without written permission. Registration entries for unpublished papers remain all rights reserved.

---

© 2026 Jair Ibarra / Rootherhub LLC.
