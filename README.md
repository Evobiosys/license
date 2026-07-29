# EvoBiosys License

A two-part copyleft-with-commercial-tier license:

1. **Base:** [Adapted Modular Public License 1.0 (AMPL 1.0)](https://github.com/Evobiosys/AMPL) — MPL 2.0 + parallel network-use clause
   exactly the text that Affero has added to General Public License, adding the A in AGPL. Lives in its own repo so other projects can reuse it.
3. **Addendum:** [`EVOBIOSYS-LICENSE.md`](EVOBIOSYS-LICENSE.md) (this repo) — adds a revenue-threshold tier on top of AMPL: organizations whose combined annual revenue meets or exceeds a significant threshold either comply fully with AMPL or obtain a commercial license from the Steward.
   This threshold is currently set to 1 million Euros.

## Lineage

```
   GPL  ─────────►  AGPL                ← the Affero step beyond GPL
                     ┊                     (network-use copyleft)
                     ┊ inspiration
                     ▼
   MPL 2.0 ───────►  AMPL 1.0           ← same step, applied to MPL
                      │                    (Evobiosys/AMPL)
                      │ + revenue-threshold
                      │   commercial-license tier
                      ▼
              EvoBiosys License         ← this repo
```

## Status

The base AMPL 1.0 text is stable. The EvoBiosys License Addendum is currently
marked `1.0-draft`; consult legal counsel before relying on it in production.

## Adopting the EvoBiosys License

Copy **both** files into your project:

- [`LICENSE` from Evobiosys/AMPL](https://github.com/Evobiosys/AMPL/blob/main/LICENSE) — the base AMPL 1.0 text.
- [`EVOBIOSYS-LICENSE.md`](EVOBIOSYS-LICENSE.md) — the addendum from this repo.

Reference both from your project README so users know they need to comply
with both. Attach AMPL's Exhibit A notice to source files (see the bottom of
the AMPL `LICENSE`).

## Steward

Evobiosys (organization). Commercial-license inquiries: see project website.

## Canonical URLs

- This repository: <https://github.com/Evobiosys/license>
- Base license: <https://github.com/Evobiosys/AMPL>
- Web canonical (addendum, when published): <https://evobiosys.org/legal/evobiosys-license>

## Official users

See [`USERS.md`](USERS.md). All EvoBiosys License users are *also* AMPL
users, since the EvoBiosys License sits on top of AMPL — see
[Evobiosys/AMPL → USERS.md](https://github.com/Evobiosys/AMPL/blob/main/USERS.md)
for the full picture.
