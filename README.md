# Evobiosys License

This repository is the canonical source for the licenses Evobiosys publishes
and stewards. Two documents live here:

- **[`LICENSE`](LICENSE)** — **Adapted Modular Public License 1.0 (AMPL 1.0)**.
  AMPL is MPL 2.0 with one addition: a parallel network-use clause (the same
  step AGPL took beyond GPL), scoped to Covered Software at the file level.
  Created under MPL 2.0 Section 10.3. Steward: Jakob Possert-Bienzle (intended
  to transfer to the EvoBioSys Foundation in AMPL 2.0).

- **[`EVOBIOSYS-LICENSE.md`](EVOBIOSYS-LICENSE.md)** — **EvoBiosys License
  Addendum to AMPL 1.0**. Supplements AMPL 1.0 with a revenue-threshold tier:
  small users, students, researchers, and non-profits stay under AMPL 1.0
  alone; organizations whose combined annual revenue meets or exceeds the
  threshold either comply fully with AMPL 1.0 or obtain a commercial license
  from the Steward. Status: **1.0-draft**.

## How they relate

```
                MPL 2.0  (Mozilla, 2012)
                   │
                   │  + parallel network-use clause (Section 3.5)
                   ▼
              AMPL 1.0   ←── this repo, file: LICENSE
                   │
                   │  + revenue-threshold commercial tier (addendum)
                   ▼
        EvoBiosys License ←── this repo, file: EVOBIOSYS-LICENSE.md
```

AMPL 1.0 stands on its own and can be reused by other projects. The EvoBiosys
License is an Evobiosys-specific addendum and only applies where it is
explicitly attached.

## Canonical URLs

- **AMPL 1.0** (base license, reusable by other projects):
  - File in this repo: [`LICENSE`](LICENSE)
  - Web canonical: <https://evobiosys.org/legal/ampl-1.0>
  - Upstream it derives from (MPL 2.0): <https://www.mozilla.org/MPL/2.0/>
- **EvoBiosys License Addendum** (this project, supplements AMPL 1.0):
  - File in this repo: [`EVOBIOSYS-LICENSE.md`](EVOBIOSYS-LICENSE.md)
- This repository: <https://github.com/Evobiosys/license>

## Using these licenses in your project

If you ship code under AMPL 1.0 alone, copy `LICENSE` into your repository and
attach the Exhibit A notice to source files (see the bottom of `LICENSE`).

If you ship code under AMPL 1.0 *plus* the EvoBiosys revenue-threshold
addendum, copy both `LICENSE` and `EVOBIOSYS-LICENSE.md` into your repository,
and reference both from your project README.

## Status

The base AMPL 1.0 text is stable. The EvoBiosys License Addendum is currently
marked `1.0-draft`; consult legal counsel before relying on it in production.
Feedback and questions: open an issue on this repository.
