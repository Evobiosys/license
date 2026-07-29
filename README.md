# EvoBiosys use of the AMPL license

How EvoBiosys licenses its published software, using the
[Adapted Modular Public License 1.0 (AMPL 1.0)](https://github.com/evobiosys/AMPL)
as the base.

**This repo is the authoritative source** for the EvoBiosys licensing terms.
The website page at [evobiosys.org/license](https://evobiosys.org/license/)
rehosts the text and syncs from here.

## The scheme, in three lines

1. **Base:** [AMPL 1.0](https://github.com/evobiosys/AMPL) — MPL 2.0 plus a
   parallel network-use clause (the same step Affero added to the GPL,
   applied to the MPL). Weak, file-level copyleft that stays SaaS-honest
   without being big-SaaS-friendly.
2. **Dual licensing:** EvoBiosys projects are offered under
   **AGPL-3.0-or-later OR EvoBiosys AMPL 1.0, at your option**. The AGPL
   option is present and unambiguous from day one so the projects remain
   eligible for FOSS channels (e.g. F-Droid).
3. **Terms of Use (the only added expectation):** any well-funded
   organization with budget, revenue, or resources exceeding **EUR 1
   million** must contact EvoBiosys sales at
   **[connect@evobiosys.org](mailto:connect@evobiosys.org)** before
   commercial use. No other restriction applies beyond this threshold. See
   [`EVOBIOSYS-LICENSE.md`](EVOBIOSYS-LICENSE.md) for the full addendum text.

## Standard source-file header

```
Dual-licensed under AGPL-3.0-or-later (gnu.org/licenses/agpl-3.0) OR EvoBiosys AMPL 1.0,
EvoBiosys's non-big-SaaS-friendly modification of the MPL (github.com/evobiosys/license)
```

## Lineage

```
   GPL  ─────────►  AGPL                ← the Affero step beyond GPL
                     ┊                     (SaaS/network-use copyleft)
                     ┊ inspiration
                     ▼
   MPL 2.0 ───────►  AMPL 1.0           ← same step, applied to MPL
                      │                    (evobiosys/AMPL)
                      │ + EUR 1M contact-sales tier
                      ▼
   EvoBiosys use of the AMPL license    ← this repo
```

## Adopting it for your project

Copy into your project:

- [`LICENSE` from evobiosys/AMPL](https://github.com/evobiosys/AMPL/blob/main/LICENSE)
  — the base AMPL 1.0 text.
- [`EVOBIOSYS-LICENSE.md`](EVOBIOSYS-LICENSE.md) — the addendum from this repo.
- The full AGPL-3.0-or-later text, if you dual-license the EvoBiosys way.

Attach the standard header above to source files, reference both licenses in
your README, and add your project to [`USERS.md`](USERS.md) via PR.

## Status

The base AMPL 1.0 text is stable. The EvoBiosys addendum is version 1.0.
