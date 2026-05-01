# terra-ust-autobuild

[![Layer](https://img.shields.io/badge/Layer-Build%20Infrastructure-7a3cff)](https://github.com/Secret-Uzbek/terra-ust-autobuild)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--6394--4912-green)](https://orcid.org/0009-0000-6394-4912)
[![Release](https://img.shields.io/github/v/release/Secret-Uzbek/terra-ust-autobuild?display_name=tag)](https://github.com/Secret-Uzbek/terra-ust-autobuild/releases)
[![Last Commit](https://img.shields.io/github/last-commit/Secret-Uzbek/terra-ust-autobuild)](https://github.com/Secret-Uzbek/terra-ust-autobuild/commits/main)
[![Release Pipeline](https://github.com/Secret-Uzbek/terra-ust-autobuild/actions/workflows/release-and-publish.yml/badge.svg)](https://github.com/Secret-Uzbek/terra-ust-autobuild/actions/workflows/release-and-publish.yml)
[![Zenodo Sync](https://github.com/Secret-Uzbek/terra-ust-autobuild/actions/workflows/zenodo-release.yml/badge.svg)](https://github.com/Secret-Uzbek/terra-ust-autobuild/actions/workflows/zenodo-release.yml)
[![Terra Audit](https://github.com/Secret-Uzbek/terra-ust-autobuild/actions/workflows/terra-audit.yml/badge.svg)](https://github.com/Secret-Uzbek/terra-ust-autobuild/actions/workflows/terra-audit.yml)
[![Central Hub](https://img.shields.io/badge/Central-FMP--CENTRAL--REPO-blue)](https://github.com/Secret-Uzbek/FMP-CENTRAL-REPO)
[![Legal](https://img.shields.io/badge/Legal-terra--legal-0f6b57)](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal)

> Build infrastructure branch for the Universal Semantic Translator: autobuild
> logic, reproducible packaging, and operational glue between specification and
> deployable artifacts.

## Layer role

This repository is a build-infrastructure layer.

It should hold:

- automated build and packaging logic;
- reproducible infrastructure for UST artifacts;
- implementation-facing documentation and release surfaces;
- a readable human entry into what the autobuild actually does.

It should not become:

- a mojibake helper shell;
- a fake DOI placeholder surface;
- a donor governance repository;
- an archive of unrelated experiments.

## Reading path

1. `README.md`
2. `CITATION.cff`
3. build-facing source files
4. `.github/workflows/`

## Ecosystem position

- `terra-ust-core` — specification layer
- `ust-mvp` — implementation layer
- `terra-translation-api` — adjacent API layer
- `terra-legal` — donor governance and standards
