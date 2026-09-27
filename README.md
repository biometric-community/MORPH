# MORPH

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FMORPH-181717?logo=github)](https://github.com/biometric-community/MORPH)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://www.faceaginggroup.com/?page_id=1453)

**MORPH** — tbiom catalog packaging for `morph` (face-recog; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/MORPH
- **Upstream source**: https://www.faceaginggroup.com/?page_id=1453
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `morph` |
| Category | `face-recog` |
| Access | `register` |
| Upstream homepage | https://www.faceaginggroup.com/?page_id=1453 |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: MORPH aging face database; commercial / academic license.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/MORPH.git
cd MORPH
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_morph.sh
```

Place licensed archives under `projects/datasets/morph/` (gitignored).

## Dataset structure

```text
MORPH/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://www.faceaginggroup.com/?page_id=1453
- Packaging: https://github.com/biometric-community/MORPH/issues
