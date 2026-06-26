# EcosVeri Launch Pack

This workspace contains the first public identity and governance files for the EcosVeri GitHub organization.

## Immediate reservation status

Checked on 2026-06-26 at about 12:47 Europe/Luxembourg time:

- `ecosveri.dev`: public RDAP returned `404 Not Found`.
- `ecosveri.org`: public RDAP returned `404 Object not found`.
- `github.com/EcosVeri`: GitHub returned `404 Not Found`.

Treat this as a public availability signal, not a reservation. The names are only secured after the domain checkout and GitHub organization creation complete in your own accounts.

## Reserve now

1. Register `ecosveri.dev` with your preferred registrar.
2. Optionally register `ecosveri.org` as a defensive redirect if the yearly cost is acceptable.
3. Create the GitHub organization `EcosVeri` on the free plan.
4. Create a public repository named `.github` in the organization.
5. Push this repository's root contents into `EcosVeri/.github`.
6. Set the organization profile:
   - Display name: `EcosVeri`
   - Bio: `Building open-source infrastructure for evidence-first AI, intelligent retrieval, search, and scientific computing.`
   - Location: `Luxembourg`
   - Website: `https://ecosveri.dev`

## Included files

- `profile/README.md`: public organization profile shown on GitHub.
- `CONTRIBUTING.md`: default contribution guide.
- `CODE_OF_CONDUCT.md`: community conduct baseline.
- `SECURITY.md`: responsible disclosure policy.
- `SUPPORT.md`: help and support policy.
- `SUPPORTED.md`: early version support policy.
- `PULL_REQUEST_TEMPLATE.md`: default pull request checklist.
- `.github/ISSUE_TEMPLATE/`: default issue templates.
- `docs/`: simple static landing page for GitHub Pages or any static host.

## GitHub Pages

After pushing to `EcosVeri/.github`, enable Pages with:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/docs`
- Custom domain: `ecosveri.dev`

The `docs/CNAME` file is already set to `ecosveri.dev`.

Suggested DNS records for the apex domain:

```text
A     @     185.199.108.153
A     @     185.199.109.153
A     @     185.199.110.153
A     @     185.199.111.153
CNAME www   EcosVeri.github.io
```

Do not add wildcard DNS records such as `*.ecosveri.dev`.

## First repositories

Recommended short names:

- `verilume`
- `needle`
- `graphforge`
- `visionstore`
- `claimcheck`
- `evalbench`

Avoid repeating the organization name in repository names. `EcosVeri/verilume` is cleaner than `EcosVeri/ecosveri-verilume`.
