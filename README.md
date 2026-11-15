# odooext-OCA-community-data-files — gren 19.0

> **Denna gren är avsiktligt tom.** Modulerna är INTE portade till Odoo 19.
> Grenen finns så att dev-miljöer (`hansolo19`) kan klona den utan att falla,
> men den påstår ingenting om att koden är portad.

## Baseline

| | |
|---|---|
| Källa | `12.0 (senaste versionsgren)` |
| Moduler | **9** |
| Grenar | `12.0`, `main` |

## Moduler

- `account_payment_unece`
- `account_tax_unece`
- `base_bank_from_iban`
- `base_currency_iso_4217`
- `base_iso3166`
- `base_unece`
- `l10n_eu_nace`
- `product_fao_fishing`
- `uom_unece`

## Blockerare

✅ Inga externa beroenden saknas i Odoo 19-kärnan eller OCA 19.0.

## Nästa steg

Portering sker på `*-pfile`-maskin med versionsagnostisk kod
(`.p.py` / `.p.xml`). Se `/skill:odoo-pfiles`.
