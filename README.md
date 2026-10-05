# secr.si / ecst.si — for sale

Static landing page for both domains.

## Live

- GitHub Pages: after DNS, https://secr.si/ and https://ecst.si/
- Source: this repo

## DNS (both apex domains)

Point each domain at GitHub Pages:

| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| AAAA | @ | 2606:50c0:8000::153 |
| AAAA | @ | 2606:50c0:8001::153 |
| AAAA | @ | 2606:50c0:8002::153 |
| AAAA | @ | 2606:50c0:8003::153 |

GitHub Pages custom domain is set to `secr.si`. For `ecst.si`, either:

1. Add `ecst.si` as an additional custom domain in the Pages settings (if available), or
2. Create a registrar URL redirect from `ecst.si` → `https://secr.si/`, or
3. Duplicate this repo with `CNAME` = `ecst.si` and enable Pages there.

Contact on the page: buy@secr.si / buy@ecst.si
